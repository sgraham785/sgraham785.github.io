# Doony Jenkins Clean Theme

This is a Jenkins CI theme that was forked from [jenkins-clean-theme](https://github.com/Dakota628/jenkins-clean-theme), then fused with [Doony's](https://github.com/kevinburke/doony) theme javascript & some of it's styles to become what it is... Doony Jenkins Clean

=================
<img src="http://doony.org/logosmall.png" alt="Doony logo" />

[Doony](https://github.com/kevinburke/doony) is a series of UI improvements on top of Jenkins. Install this to make
your Jenkins user experience much better.

[jenkins-clean-theme](https://github.com/Dakota628/jenkins-clean-theme) is a simple theme for jenkins using the "simple-theme-plugin"

## Who's Using Doony

Doony was made at [Twilio]( https://www.twilio.com ). It's also been forked/starred by
employees at:

- Panic, Inc
- the BBC
- Instagram
- Netflix
- eBay
- Groupon
- Mail.ru

### Before

<img src="https://api.monosnap.com/image/download?id=tyH5frYrtWOizYJLkxWstROHM" />

### After (it's a cross between the images below)

![Screenshot](http://img560.imageshack.us/img560/3152/pwrt.png)

<img src="https://api.monosnap.com/image/download?id=aoqX9gzkqqEPa8IbKvEknmdug" />

<img src="https://api.monosnap.com/image/download?id=12w3g9i5oU8uEBQSqV8okgwXJ" />

<img src="https://api.monosnap.com/image/download?id=YDWD8TzKBUhBk8j3MwmsXy7Mn" />

## Features

- There's a "Build Now" button on every build page. The button will redirect
  you to the console output of the new build. You can also easily cancel the
  current build.
- The orbs are gone! Replaced with flat circles and circular in-progress bars.
- Click targets in the left hand menu are much bigger (they expand to fill the available UI)
- The fonts are bigger and cleaner.
- More spacing in between list items.
- Removes a lot of the useless icons
- "Console Output" looks more like a console.
- Replaces fonts.
- Hover menus have a pointer cursor, indicating clickability
- Text inputs are friendlier, bigger
- Homepage has an option for "view console output of latest test"

## Installation in Jenkins

If you do install your Jenkins environment it's probably best to embed it in
the default Jenkins styles.

1. Install the [JQuery Plugin][jquery]

2. Install the ["Simple Theme" Plugin][simple]

3. In Jenkins, click "Manage Jenkins", then "Configure System", then specify
   the CSS and Javascript URL's for this theme. You should find a place to host
   these, on a static server inside your cluster.

    You can use these URL's:

        - https://rawgithub.com/sgraham785/doony-jenkins-clean-theme/master/doony-clean.js
        - https://rawgithub.com/sgraham785/doony-jenkins-clean-theme/master/master.css
    Alternatively you can let Jenkins self host these files by putting them in `~/.jenkins/userContent`
    With the default Jenkins settings the files you use will then be:

        - http://localhost:8080/userContent/master.css
        - http://localhost:8080/userContent/master.js

    Here's a screenshot of the settings page:

    <img src="https://api.monosnap.com/image/download?id=qtiCAUev2R3yS46He5LHwQXUS" />

[jquery]: https://wiki.jenkins-ci.org/display/JENKINS/jQuery+Plugin
[simple]: https://wiki.jenkins-ci.org/display/JENKINS/Simple+Theme+Plugin

4. Click "Save". Enjoy!

## Compatibility

This will "work" against the latest version of Jenkins, currently 1.532. It may
work with older versions but this is not guaranteed.

## Notes

- I included the original LICENSE from Doony cause it said so =)

- This is very much a work in progress, feel free to file bugs/issues and I'll make improvements as I can.

- This project is in no way intended to slam Jenkins developers. Jenkins is
awesome, and unlike Travis you never get a blank screen. They are working
within a series of vastly different constraints than I am. Consider:

    - they have to support every browser/platform/language
    - any change they make will make part of the userbase angry
    - every change has to be completely open-source friendly in every way

