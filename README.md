**No offense, but your bug report sucks.**

Don't take it personally. I used to write some really sucky bug reports myself. 

But then I got a job as a lowly programmer at a certain fruit company, where they take internal bug reporting fairly seriously. That's where I learned how to write great bug reports.

 I'd like to share what I've learned so you can write great bug reports too!
 
 *Turns Out*™, writing a great bug report is surprisingly easy. A great bug report also vastly increases the chances that the bug will get fixed.

You've taken the step of contacting the devloper to report the bug, so clearly, you want this bug to be squashed. The best thing you can do to ensure that happens is to write a great bug report. And honestly, it only takes a few extra minutes.

 I'd like to share what I've learned so you can write better bug reports too!

---

The best way to describe a great bug report is to start with an example:

```
SUMMARY
------------------
Enabling AppleID two-step verication prevents logging into iTunesConnect mobile app on iOS

CONTEXT
------------------
Device: iPhone 5S
OS: iOS 7.3
App: iTunes Connect.app

STEPS TO REPRODUCE
------------------
1. Register as Apple iOS developer on developer.apple.com
2. Enable "Two-step verification" for your Apple Developer account at https://appleid.apple.com/account/manage/security
3. Install iTunesConnect mobile iOS app on iOS device  https://itunes.apple.com/us/app/itunes-connect/id376771144?mt=8
4. Lauch iTC. See login screen.
5. Login with AppleID credentials

EXPECTED RESULT
------------------
Login should be possible, and iTC should use 2-step verification by sending a text message of some kind with a 1-time expiring login code

ACTUAL RESULT
------------------
After submitting login form, an error dialog appears with the message: "Error logging in. Please try again."
```

---

A great bug report always contains the following essential components:

1. SUMMARY
1. CONTEXT
1. STEPS TO REPRODUCE
1. EXPECTED RESULT
1. ACTUAL RESULT

    *If you're feeling especially helpful, one additional component is always appreciated:*

1. ADDITIONAL NOTES

Let's break these down.

1. SUMMARY
    
    A one (or maybe two) sentence, high-level description of the problem. This is almost like a subject line of an email.
    

1. CONTEXT

    This is where you tell the developer about your setup. Three things are vital:
    
    1. The hardware device you're using (`iPhone 5S`, `2013 MacBookPro Retina`, etc)
    1. The OS version you're using (`iOS 7.2`, `OS X 10.9.4`, etc)
    1. The specific version of the app you're using. Include build numbers if possible. (`Mail.app Version 7.3 (1878.6)`, `TextMate version 2.0-alpha.9551`)
    
    If you're reporting a bug on a website, substite the app name and version for the name and version of the web browser you are using.
    
1. STEPS TO REPRODUCE
1. EXPECTED RESULT
1. ACTUAL RESULT
