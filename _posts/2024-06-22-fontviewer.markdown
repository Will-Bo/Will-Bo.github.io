---
layout: post
title:  "FontViewer"
date:   2024-06-22 10:34:28 -0400
categories: projects
---


In my OOP class, I became quite interested in Java’s Font class so I decided to write a personal project involving the Font class. The result is FontViewer, a program that I wrote to preview what fonts are installed on your computer!

!["A screenshot of the main FontViewer screen with some sample text. The font is Monospaced Bold."]({{ site.url }}/assets/FontViewer1.png)
*A screenshot of the FontViewer application. It shows text that the user has input, as well as options to change the font. FontViewer comes with no default text in the text field — I typed this in and set the font to Monospaced Bold, then pressed the “Apply Font” button.*

FontViewer consists of a title (FontViewer!), a pane where you can type (all of the text in the blue-outlined pane is user-typed), and options at the bottom of the panel to change font settings. These settings include the font family, style and size, as well as a button to apply the changes to the application’s text.

!["A screenshot of the main FontViewer screen with some additional sample text. The font has been changed to RIT Rachana."]({{ site.url }}/assets/FontViewer2.png)
*A screenshot of FontViewer using a new font (RJT Rachana), which has been selected in the drop-down and applied to the text. A demonstration of a new font applied to FontViewer.*

FontViewer was an extremely rewarding project to work on. We learned AWT in my OOP class, which is a dated mechanism for writing Graphical User Interfaces in Java. As a part of FontViewer, I decided that I wanted to learn how to use JavaFX instead, which is a modern GUI library. As I looked into using JavaFX, I saw recommendations to use Maven (or another dependency management system) to make sure that it is easy to set up a development environment for JavaFX, so I did! As a result, I gained a lot of experience with JavaFX and Maven through my project. What started as a basic project to play with the Font class turned into a real program that served as a learning ground for dependency management and GUI construction.

I feel that FontViewer is one of my most significant personal projects. Despite its simple functionality, FontViewer embodies many of the elements of a complete computer application — user interaction, a GUI, and use of libraries — and was an early example of a project where I saw something in a class and thought to myself “that’s cool, I want to make something that explores that further”. I hope to be able to continue to develop FontViewer with more features in the future! Its repository is located on my [GitHub as FontViewer](https://github.com/Will-Bo/FontViewer).
