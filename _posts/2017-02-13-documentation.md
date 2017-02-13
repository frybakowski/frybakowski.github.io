---
layout: post
title: Real-time web application with MeteorJS
description: Review of MeteorJS, full-stack JavaScript platform for building web and mobile application in real time, created with JavaScript.
img: meteor.jpg
color: 212121
author: frybakowski
---

* some text
{: toc}


#Real-time web application with MeteorJS

	In wide, web technologies world, the most common and generally use technology for client-server communication actually is HTTP. This protocol, of course like eveything has advantages and disadvantages. One of weak points of HTTP protocol is lack of synchronization between client and server.

What can it means?

Generally, it means, that every changes made in application data base are not automatically pass to client part of application and user cannot see it on interface. However, there is a sollution for this communications issue. It is WebSockets technology. This technology uses MeteorJS, which I want to present.


#Real-time is cool.

	Beneffits from synchonizing our web system in real-time, seems to be visible at a glance. We have possibility to create web systems and applictions more similar to native applicaion or even operation systems. To visualise it I will use example.

How works todays operation systems?

Let’s imagine operation system in which we open two windows of file manager. Both windows are open in the same location. Next, in first window we create new folder. Suddenly, we can see this change in second window, automatically, in magic way! This is our real-time effect.

This approach is user-friendly, but not only. It’s also very usefull for business logic, which in some cases is even necessary. For example some chats, web games or systems which observe some different types of states requires real-time approach.



Of course, as it happens in life, communication based on WebSockets technology has also “dark side”.  For example it’s more limits in case of counts of users, which can use our application / system than in communication based on HTTP. Decision, which solution we should use in case of our product, base on it’s destiny. Despite all cool features, which gives us real-time communication, in some cases better approach is communication based on HTTP. However, as I mentioned, there are some situations where real-time communication is required.


#MeteorJS as full-stack platform.

	Let’s focus now on  MeteorJS’s architecture. Whole solution based on JavaScript language and it is comprehensive platform, allows developers creating applications from beginning to the end.

What it means for developers and whole process of software’s creating?

Thanks to fact, whole platform is made with JavaScript, both client and server side based on this language, which means developers using this platform need only one programming language, to be available to create whole application. It is also very useful in case of communication between client-server. Developers can avoid different issues with data formats and it exchange. MeteorJS uses MongoDB as it data base.

Huge advantage of MeteorJS is it’s simplicity (in positive mean) from developer perspective. Communication client-server is very intuitive, and it’s data synchronization is making automatically, thanks to this, we get real-time effect for free! All these points makes whole process of software creating very quick and efficient.



#Back-end in MeteorJS.

	Server side part of MeteorJS’s base on NodeJS technology. It supports also very nice and intuitive build system, which base on npm (Packages manager of NodeJS). It provides set of packages for MeteorJS called Atmosphere.js


#Front-end in MeteorJS.

	Client side part of MeteorJS provides us very wide set of front-end technologies. It supports technologies like Angular,  React or created specially for MeteorJS needs, templates system called Blaze.

#Conclusion
    MeteorJS is complex solution for web and mobile application (It support also Apache Cordova). Development is fast, because of fact using only one language on client and server. Communication based on WebSockets gives us real-time effect. This type of communication is specific and it should be used in specific situation, which requires it. Apart from this, I can definitely recommend this platform,  which can be confirmed by the fact of still growing count of applications and systems build with MeteorJS and big community around this solution.