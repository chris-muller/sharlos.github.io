---
layout: project
title: "Simple Scales"
description: "A simple way to update your weight using the native HealthKit API."
link: "http://rocketvector.com/simple-scales/"
order: 50
image: /img/simplescales-1.png
---

![]({{site.baseurl}}/img/simplescales-2.png#simple-one){:class='no-shadow'}

Simple Scales is an iPhone application that makes regularly enetering your weight into iOS HealthKit data store simple. The app uses a custom-designed input to make entering your data simple and seamless. 

In addition to saving your mass to HealthKit, Simple Scales also uses your height data to calculate and save your BMI (Body Mass Index), giving you an easy glance at how your weight is tracking.

### Process and Contribution
With recent changes to the user interface of HealthKit, it became obvious how inconvenient adding your weight to HealthKit was if you weren't using a smart scale, especially if you were tracking your weight daily.

After brainstorming with an experiance designer to figure out the ideal input method for updating a single number that didn't significantly change in value, the scale slider was settled on. It allows the user to update their weight with the most recent incremental change.
The current mass displayed to the user is also updated as the user scrolls, providing realtime feedback to the user. To give the input greater physicality the new haptics API was used to gently vibrate the phone as the user scrolled through the scale, or when a weight value is saved.

Native HealthKit unit transformation was used to localise the input and saved data for the user no matter what region they were from.

### Technology Used
* iPhone application is coded completely in Swift using Xcode.
* The app uses the HealthKit API and data store extensively.
* A custom input method was created making use of a customed collection view.
* A dynamically created image using CoreGraphics was used to allow users to share their current weight with friends using the sharesheet.
* The application uses Git as its version control with issue tracking managed in Bitbucket and project management managed in Trello.
