## THIS PROJECT IS A MAINTINED FORK

This repository is an independent fork of the original Intel project, created after retirement from Intel so development could continue outside the original upstream lifecycle. It is maintained here for continued use, experimentation, and community-driven improvement.

# Board-Instrumentation-Framework
This project allows you to instrument and graphically display pretty much anything you want in a flexible way. 
It consists of 3 parts, the data collector (Minion) written in Python, which sends data over a UDP socket to the data broker and recorder called Oscar, also written in Python.  The last part is a Java FX application called Marvin, which receives data from Oscar and displays it via a library of highly configurable 'widgets'.

Here are a couple of my YouTube videos that make use of this framework:
https://www.youtube.com/watch?v=6UUFWZs-Sck
https://www.youtube.com/watch?v=NYI8BDv17Lw


Take a look at the 200+ page BIFF Instrumenation Framework User Guide.pdf file for details: https://github.com/PatrickKutch/Board-Instrumentation-Framework/blob/main/BIFF%20Instrumentation%20Framework%20User%20Guide.pdf.
