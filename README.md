# Your First App

This is a very, very simple Android Studio project for the [Android Basics Nanodegree](https://www.udacity.com/course/android-basics-nanodegree-by-google--nd803) by Udacity and Google.

The goal was to design and implement a single screen app that displays information about a fictional small business (our favorite coffeeshop, local restaurant, or that gem of a store that sells those rare comic books or records). I have dedicated this app to my friend's business, [Minerva Peyús Intelligent Beauty](http://minervapeyus.com/).

![Portrait orientation](https://github.com/dburgosp/SingleScreenApp/blob/master/portrait-img.jpg?raw=true)

![Landscape orientation](https://github.com/dburgosp/SingleScreenApp/blob/master/landscape-img.jpg?raw=true)

# Project Specifications

## Content Review
**Design includes all specified business criteria**. Design must include:

* Business name
* At least one photo representing the business
* Two or more other pieces of information, such as:
  * Contact information for the business (eg phone number, email address, website)
  * Address of the Business
  * Description of business
  * Hours of operation
 
## Functionality
1. **Program compiles and runs on a phone**. Program must function in Android Studio emulator and on a phone. Upon launching on a phone, the card appears.
2. **Content does not appear "cut off"**. Layout scales responsively for screen sizes in portrait mode, with no part of any images only partially visible. Student is not responsible for responsive design in landscape mode. Note: Reviewers will test on a Nexus 5X which has a screen size of 5.2 inches (132.08mm). It is advised you test on this size at minimum. If your content does not fit on this size, consider implementing a [ScrollView](https://developer.android.com/reference/android/widget/ScrollView.html).
 
## Code Review
1. **At least one View Group is included**. XML must include a Relative Layout and/or a Linear Layout.
2. **View Groups contain at least one image view and at least one text view**.  Must have one or more image views or text views.
3. **Elements and Text on screen are in appropriate units**. Elements are specified in dp, text is specified in sp.

## Notes
1. I have used different dimens.xml files for mdpi (by default), hdpi, xhdpi, xxhdpi, xxxhdpi and tvdpi. 
2. For the different sizes, I tried to use the [Dimenify](https://plugins.jetbrains.com/plugin/9349-dimenify) plugin for Android Studio, which automatically should have created every dimens.xml for every density, but it didn't work fine for me, so I fixed all the values manually later.
3. I have also created a second layout for the landscape orientation.
