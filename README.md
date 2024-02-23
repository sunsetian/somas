SOMAS

v4.12

Setian Organic Machines

This is the first open version of the Somas: Visual interfaces for VJing, Projection Mapping, and Generative Video.

This Touchdesigner file contains the open-source project to be used and transformed in any way the developer wants.

No guarantee is given. Use at your own risk.

Please give attributions to the previous authors.


WHAT IS SOMAS?

SOMAS is a VJing interfacing tool to help set up the generative video algorithms for a VJ set or a live video show with Touchdesigner. SOMAS stands for Setian Organic Machines, while Setian stands for Signals, Electronics, Techno, Interactive, Art, and Networks.

The idea behind SOMAS is to provide a flexible and stable framework to host your own video processes. It provides an intuitive and easy-to-customize interface with ready-to-use-and-modifiy Containers, that are strategically wired to the interface so you don't have to worry about dealing with the load of your CPU when having many different SOMAS at the same time.

HOW TO USE?

The main project container, called Setian_VOM, holds the SOMAS INTERFACE and contains all the code. To use it View it as a separate window, right-click over the Setian_VOM name, and select the view option. You'll find a visual interface, as a very rough VJing software. Here you have three main sections. To the Right are all the different SOMAS which are available in your set. To the Left, you have the Controls for the active SOMA, and in the center, you have the Main Output source and post-processing of the video signal, which is common for all the SOMAS.

From here you are able to go inside any of the SOMA containers, in the operators called containerVisual1, containerVisual2, containerVisual3, and so on, and change them in whatever way you want or need. Just be sure to keep the "NullFinal" operator and the "bg" text operator.

To create and modify the Controls, you need to go inside the containerControls1, containerControls2, containerControls3, etc, and create the buttons and sliders you need, and connect them through code following the same structure as the other sliders and buttons to communicate with their relative conteinerVisual.

VIDEO INTRODUCTION

Here you will find the video introduction for the SOMAS project HOW TOS.



Creative Commons
Sebastian Gonzalez Dixon 2024
