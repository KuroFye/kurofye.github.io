---
layout: post
title: My work with MOTIONS
summary: Undergraduate Thesis on Unity3D and Interfaces
---

All of my undergraduate thesis, that lasted for 2 semesters, was done on developing MOTIONS inside Unity3D. It is a researcher-oriented platform that allows the user to perform different kinds of evaluations on human-information interaction using a wide variety of interfaces.

<span class="image featured"><img src="{{ site.baseurl }}/images/mot1.png" alt=""/></span>
You can learn more about the proyect [here](http://motions.informatica.usach.cl/)

I did not started the whole system on my own, i started on the undergraduate thesis VORTICES of my colleague Esteban Gaete and made his software architecture more modular, extended his functionalities, developed a more user-oriented and code-free configuration UI and added support for [Emotiv Insight](https://www.emotiv.com/) and [NeuroSky: Mindwave](https://store.neurosky.com/pages/mindwave) portables EEG as well as eye-tracking with the now vanished EyeTribe.

Besides from developing the plugins for the aforementioned devices i also created a software structure that allows for new visualizations, environments, objects and interfaces to be added as independent as possible from the rest of the code, so each new addition to the system do not affect the work already done on the project. 

As there are no fixed inputs (because the idea is to try new ways to interact with information) i also created a system that allows any hardware (or software) input to be paired to any action in the system by the user, without touching any code and during execution time. For example, keyboard, mouse and mental statuses are all input that can trigger different actions in the system. Actions can be to zoom into an image, rotate the sphere showing the images (as shown below) and so on.

<span class="image featured"><img src="{{ site.baseurl }}/images/mot3.png" alt=""/></span>
>Configuration to pair any inputs to any action.

<span class="image featured"><img src="{{ site.baseurl }}/images/mot2.png" alt=""/></span>
>Sphere of loaded images, work of Esteban Gaete.

My full work will be available online as soon as the final version is greenlighted by the commision assigned by the University.

Any question regarding working with EEG, Eye Tracking or the system’s structure please feel free to contact me, happy to help!