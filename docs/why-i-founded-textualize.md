---
hide:
   - navigation
#   - toc
---

# Why I Founded Textualize

I founded Textualize with the express purpose of reversing what I saw as years of neglect in a critical developer tool: the terminal. That little window and flashing cursor that is the starting point and constant companion for many a software project.

Neglect may be nothing new in the tech world. When we collectively decide that the new generation of software has arrived, we neglect what came before it. It's a natural consequence of progress and no bad thing.

What's different about the terminal is that nobody got the memo that we should stop using it. The browser, with all its power, is seen as a companion to the terminal by developers, not as a rival. Terminals appear to reside in a niche they are so ideally suited for that tech Darwinism can't touch them. In a 2022 survey of developers, 89% responded that they have a terminal open at least half of the day. Clearly developers are as engaged with the terminal as much as the browser, and yet few tech companies give it more than a second thought.


## Rich 

<div class="admonition tip inline end">
<p class="admonition-title">Rich for Python</p>
<p></p><div>
    </div><a href="/images/rich.svg" target="_blank">
     --8<-- "docs/images/rich.svg"
</a></div>

I see the neglect in the terminal world as a mistaken assumption that whatever can be done in the terminal, has been done, and there is little to gain from attempting to enhance the terminal experience. My work on [Rich](https://github.com/Textualize/rich) made it clear to me that developers were delighted by any visual enhancements. Not only was innovation still possible with a technology older than most developers, but there was real demand for it.

Terminals and browsers coexist so comfortably in developer's minds because there are distinct use-cases for each; we instinctively know when to reach for one over the other. Yet there is a class of terminal application that defies such an obvious taxonomy. The TUI, or Text User Interface, is an application which takes over the terminal and can present windows, views, and dialogs. There was a time when these apps were the primary way of interacting with a computer. That era is long gone. Yet, like the terminal itself, TUIs survive to this day. In fact, they are more popular than ever.

There are some technical advantages to these apps: a developer can operate a TUI over an encrypted channel on a remote server. But this is often not the primary or even secondary reason why a developer would reach for a TUI over a web application.

TUIs can transition seamlessly from the command line and back again without interrupting the developer's train of thought, which explains some of their popularity. TUIs are also popular for many of the reasons that terminals themselves are popular: a minimal keyboard-focused interface that rewards repeated use. One that is free of distractions and context switching. Additionally, terminals are a natural fit for the clean lines, dark mode, aesthetic that even web apps seek to emulate. 

Having talked to many developers on the subject, I understood that there were few use-cases where a developer would not want a TUI. Many enthused about TUI interfaces to system administration tasks, network automation, internal analytics, and crypto currency bots, but for every work related application there was a desire for a productivity tool, calendar, distraction-free writing and any number of apps were developers would eschew the web or desktop in favor of a TUI.

There is clearly demand but short supply. TUIs have traditionally been built with an API conceived in the 90s. There has been almost zero innovation since then. Neglect meant that none of the advancements in the world of application development made it to the terminal.

## Textual

My answer to this is [Textual](https://github.com/textualize/textual), a project I started in 2021 to take the best of innovation from the web and desktop world and bring it to the terminal. The prospect of being able to build TUIs without grappling with archaic tools created a lot of buzz in the Python community and beyond.

<figure style="width:450px;">
    <a href="/images/textual-screenshots/cloudtrail.svg" target="_blank" >
        --8<-- "docs/images/textual-screenshots/cloudtrail.svg"
    </a>
    <figcaption>An app built with Textual</figcaption>
</figure>



The first iteration of Textual was a hobby project, created to pass the time and satisfy some intellectual curiosity. Only once I was satisfied that there were no technical reasons as to why this had never been attempted, did I realize there was opportunity here. The unique characteristics of TUIs, namely low systems requirements, cross platform, remotely accessible, could find a previously unexplored niche -- which only Textual could fully exploit.

I would not want Textual to stray from its roots as Free and Open Source software, but selling "picks and shovels" would not compromise that. The opportunity felt compelling enough for me to quit my job in late 2021 and live on savings for a year. At the end of the year I would have built Textual and a related web service which I could then turn into a business. 

Founding Textualize was very much a plan B. But funding enabled me to be more ambitious in my mission to rejuvenate the terminal. Our next challenge as a company is to solve the problem of distribution. Paradoxically, although terminal software is installed on every desktop computer ever shipped, the terminal is little known outside of developers and other technical users. If TUIs are to truly reach their potential we need to make them accessible to more typical users.

I see Textualize as the vanguard in a terminal renaissance. I don't know why there is renewed interest in the terminal as a platform now. We could have asked more of terminals years ago. But we are in a unique position to halt and reverse years of neglect.

[Will McGugan](https://twitter.com/willmcgugan)

** CEO / Founder **

