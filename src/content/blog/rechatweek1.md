---
title: "This Week in ReChat #1"
description: "When the tour fails to guide you"
pubDate: "Mar 19 2023"
heroImage: "/TWIRC.svg"
---

Welcome to "This Week in ReChat"!

Today I'm going to show something new while I develop from my client. Some feature has been implemented in this week, there's some new features and changes during development.

# Features

## Tour

ReChat was designed for easier to use for some people who use desktop or mobile

So I decided to add it just to guide people since they don't know what to do next after login, this is why I need to implement it

But yet, I started to implement the `Toolbar` and `Container` first, I've been doing correct way (since my brain can do it now instead doing lazy as hell)

![Current implementation ](/assets/Tour.png)
This is the current version of this tour since I implemented. (But those guide is so worse than I think.)

Also, if you notice those images, they were rendered in blender (yeah I made it BTW), I just waited a bit longer than expected since my laptop can run barely in some render (I hope my laptop won't melt himself while rendering)

![God, help me what I am done](/assets/godno.png)

This thing, I've tried to make a checkmark, but it just ended badly, that why I'm *literally* almost new at blender for some reason.

## Appearance

This feature that I wanted to create by myself (since I like to make my client customizable). I created a color system (using `SUID`, trying to don't mess with `createTheme` thing)

So recently I added something like emoji (like Revite has) and some variant form `AppBar` and I tried to add modes like Light and Dark Mode, but sadly `SUID` cannot do that since thinks it is a boolean or some shit. That why I'm not going to add this app mode.

![Appearance](/assets/apperance.png)
Some options that you are able to do, but soon I'm going to try and implement App Modes later this week.

## Status Text and Custom Status

So recently I checked Solenoid's codebase just to see how it works, one thing that the custom status and prefab uses `ReChat.ts` or `Solenoid.ts`, recently I've started implementing using components that `SUID` provides, this started *very well*, but it was good yet. Those things are currently changing and setting things up just to make sure it works.

![Custom Status and Status Text](/assets/status.png)

This feature is not completed yet but still to be improved yet

## Markdown Support and Description in Channel Sidebar

I started to just add a "minor" change related to `ChannelSidebar`, I added now the markdown support to Channel name and description just for users can understand where to.

These changes *might* help some users what were to go.

![Channel Sidebar with markdown and description](/assets/markdown+desc.png)

# Compatibility

ReChat for compatibility was made just for "*mobile*" but still can be used for desktop, I've checked now if ReChat can be used in the sidebar, it works flawlessly without problems as for now I tried to fetch any message from Revolt Lounge it still works but the side might need to be fixed later

![ReChat in Edge's Sidebar!!!!!!!](/assets/sidebar.png)

# That it for today!

Those features and changes I've showed this week since I was bored while I'm developing for my client. Happy reading!