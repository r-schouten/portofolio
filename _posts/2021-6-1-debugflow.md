---
layout: post
title:  "Debug flow"
summary: "A flexible debug manager"
author: ReneSchouten
date: '01/06/2021'
thumbnail: /assets/img/debug_flow.jpg
permalink: /projects/debugflow/
category: jekyll
keywords: devlopr jekyll, how to use devlopr, devlopr, how to use devlopr-jekyll, devlopr-jekyll tutorial,best jekyll themes
usemathjax: true
---
[Github link](https://github.com/r-schouten/debug-flow)

This project is currently in development.

Debug flow is a debug manager that will make debugging with console logs easier and more flexible. The most development environments have a simple console with almost no options, even changing the log level on the go is usually not possible. Debug flow goes far beyond that.

Debug flow is seperate fromdevelopment environments, it support all kinds of input sources, much different filters can be applied and there are different ways to show the output. The goal is the let developers build a convenient debugging environment within a few minutes that saves hours of debugging.

A few examples:

-    input from executable
-    input from serial ports
-    input from sockets
-    input from file
-    filtering on log level
-    filtering on tag
-    hiding log context
-    adding colors to specific text
-    splitting to different windows
-    saving to file
-    show data in console
-    show html context
-    console with real time filtering
-    console with collapsible tree debugging
-    showing a measurement on a widget
-    showing measurements in a graph
-    showing measurements in a table
-    synchronizing all windows with a timeline
-    outputs to communicate back
-    custom nodes

And so on, to make that possible in a user interface the application works with flow programming, where each of that function is a node. The goal to make it possible to change the flow real time with backwards updates.

The application is writen in C++ using the Qt framework.

It will take some time before the first stable version will be released.