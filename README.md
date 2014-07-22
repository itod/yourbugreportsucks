**No offense, but your bug report sucks.**

Don't take it personally. I used to write really sucky bug reports myself. 

But then I got a job as a lowly programmer at a certain fruit company, where they take internal bug reporting fairly seriously. That's where I learned how to write great bug reports.

I'd like to share what I've learned so you can write great bug reports too!
 
 ***Why should I care about writting great bug reports?* I hear you ask.**
 
You've taken the step of contacting the devloper to report the bug, so clearly, you want this bug to be squashed. The best thing you can do to help, is to write a great bug report. This will vastly increase the chances that the bug will get fixed in a timely manner.

And honestly, it only takes a few extra minutes. *Turns Out*™, writing a great bug report is easy!

---

**A great bug report always contains the following essential parts:**

1. SUMMARY
1. CONTEXT
1. STEPS TO REPRODUCE
1. EXPECTED RESULT
1. ACTUAL RESULT

    *If you're feeling especially helpful, one additional component is always appreciated:*

1. ADDITIONAL NOTES (OPTIONAL)

Let's break these down.

1. SUMMARY
    
    A one (or maybe two) sentence, high-level description of the problem. This is almost like a subject line of an email.
    

1. CONTEXT

    This is where you tell the developer about your setup. Three things are vital:
    
    1. The hardware device you're using (like `iPhone 5S`, or `2013 MacBookPro Retina`)
    1. The OS version you're using (like `iOS 7.2`, or `OS X 10.9.4`)
    1. The specific version of the app you're using. Include build numbers if possible. (like `Mail.app Version 7.3 (1878.6)`, or `TextMate version 2.0-alpha.9551`)
    
    If you're reporting a bug on a website, substitute **the name and version of the web browser you are using** for the app name and version.
    
1. STEPS TO REPRODUCE
    
    **This is the most important part**. Break the issue down into a specific numbered list of steps that always (or at least sometimes) reproduces the problem. 
    
    Seriously. 
    
    A numbered list of steps.
    
    That's all we really need.
    
    **A numbered list of steps.**
    
    Did I mention we need ***A NUMBERED LIST OF STEPS***?
    
1. EXPECTED RESULT

    Sometimes the desired outcome you expect is not obvious to the developer. Just to be safe, spell it out here in one short sentence or phrase.

1. ACTUAL RESULT

    This is what you've been waiting for! Here's your chance to describe what is actually going wrong. Make this section as long and detailed as you like. In fact, rant away! Since you've already provided **a numbered list of steps** to reproduce the problem (you did provide a numbered list of steps, didn't you?), you're now free to complain all you like about what's going wrong!
    
    If the app crashes, describe that here, and include the entire crash log, please!
    
    *And Finally, the optional part:*

1. ADDITIONAL NOTES (OPTIONAL)

    If you're feeling especially helpful, fee free to provide additional info here. 
    
    If you're reporting a bug in a website, did you try to reproduce it in multiple browsers? (That's always a great idea, BTW.) Great! Tell us about it here!
    
    If you're reporting a bug in a Mac app, did you simultaneously run Console.app and capture some suspicious-looking console logs? (That's always a great idea, BTW.) Great! Tell us about it here!
    
That's it! Thanks for reading.

Below is a template to get you started. Please copy it use it as a starting point. (Did I mention we need **a numbered list of steps to reproduce**?)
   
--- 

    SUMMARY
    ------------------
    *<REPLACE ME WITH A HIGH-LEVEL DESCRIPTION OF THE PROBLEM IN A SENTENCE OR TWO>*


    CONTEXT
    ------------------
    Device: *<DEVICE + VERSION HERE>*
    OS: *<OS + VERSION HERE>*
    App: *<APP OR BROWSER + VERSION NUMBER HERE>*


    STEPS TO REPRODUCE
    ------------------
    1. *<STEP ONE>*
    2. *<STEP TWO>*
    3. *<ETC>*


    EXPECTED RESULT
    ------------------
    *<WHAT DID YOU EXPECT>*


    ACTUAL RESULT
    ------------------
    *<WHAT WENT WRONG>*


    ADDITIONAL NOTES
    ------------------
    *<CRASH LOGS, CONSOLE ERROR MESSAGES, AND OTHER OPTIONAL INFO>*