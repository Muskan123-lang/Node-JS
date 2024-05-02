# Node-JS
-> Node.js is an open-source runtime environment that allows JavaScript code to be executed outside the browser. 
-> It is based on the V8 JavaScript engine of Google Chrome.
-> It is mainly used for backend development.
-> Since it aims to provide dynamic content, entire sites may be operated using a single stack, which accelerates development and maintenance and liberates 
you to concentrate on the project’s commercial objectives.

-> Applications may open, add, and remove files on the database in real-time with ease using node.js. 
-> node.js is a runtime environment rather than a framework. 
-> A JavaScript engine in a runtime environment parses developers’ code using Web APIs they can access. This makes it lightweight, adaptable, and simple to 
deploy—all characteristics that will help you optimize and accelerate the development of your application.
-> Javascript modules included in the extensive Node.js library make it easier to construct web apps.

# Features of Node.JS 
The following capabilities greatly simplify the software development process for developers.
* V8
* Asynchronous
* Single-Threaded
* Unified API
* Data Streams

V8 
-> To convert javascript code to native machine code and then execute it, Google created the open-source V8 javascript engine for Chrome. This makes it possible for
better and quicker runtime performance.

Asynchronous
-> The speed at which a website or application loads is greatly improved by using node.js. This is due to node.js’s ability to handle numerous requests concurrently 
without waiting for each request’s completion. Non-blocking code execution is a design paradigm popular among developers and is one of the main causes of its popularity.

Single-Threaded
-> Using the single-threaded event loop approach, Node.js can manage multiple clients without the need to establish additional threads. This eliminates the 
performance hit associated with thread context switching and stops problems brought on by improper thread synchronization, which can be very challenging to fix.

Unified API
-> Node.js adopted well-known server-side development principles, making it simple to combine with a JSON-compatible browser or database to create a unified JavaScript
development stack.

Data Streams
-> Due to the Stream module, Node.js applications never buffer any data. Building objects that implement the stream interface is simple thanks to the stream module,
an abstract interface for interacting with streaming data.

(The JavaScript runtime is particularly well suited for developing scalable network applications because it makes it simple to output data in chunks, giving Node.js
developers the power of composability in their code.)



# What is Node JS Used For?
-> Node.js is used in practically all of the applications we use daily because of its ubiquity, which makes development easier and improves browsing.

Here are some instances of node.js’s use and how it helps consumers enjoy a seamless browsing experience: 

Chat Applications
Streaming Applications
Browser Games
Real-Time Collaboration
Internet of Things


# Chat Applications
-> Today’s social media sites that we use almost all have chat functions available. Text, audio, or video messages can be transmitted from the sender to the recipient during a chat. When you send a text, you can receive discussions from your other contacts and the person you are texting. Node.js is to thank for this.
-> All necessary tools are available in Node.js for building dynamic conversations of any intricacy. Node.js uses the Socket.IO module to enable real-time, bidirectional, and event-based communication between the browser and the server.
-> Additionally, Node.js offers a powerful Event API that makes it simple to build emitters that regularly emit named events that event handlers will listen to. This functionality simplifies the creation of server-side events and the ubiquitous push notifications used in text messaging and other dynamic applications.

# Streaming Applications
-> If you enjoy watching movies or TV series on Netflix, you’ll be astonished to learn that the incorporation node. This is why the well-known video platform can provide the perfect streaming service to you and millions of other customers worldwide.
-> You are only downloading the app when you download the streaming application. Later, the server streams the video material to your device. Suppose you’re wondering how; it’s all because of the Stream API in node.js. By allowing portions of the app’s executable code to be sent to the local computer, the API maintains a connection that may be used to download other components as needed.
-> Because of this, streams need an open connection to transmit application data from one location to another, not caching or temporary data. Node.js’s real-time and streaming operations are made incredibly simple and effective by its asynchronous, non-blocking I/O capabilities.

# Browser Games
-> Games are typically downloaded to computers or mobile devices and then played later. However, certain games can be played directly in the browser without downloading an app.
-> To design single-player and multiplayer games that function directly in the browser without the need to install any third-party plugins, Node.js is combined with technologies like HTML5 and Socket. IO.
-> Additionally, it offers game designers several tools that help them manage the complexity of multiplayer games.

# Real-Time Collaboration Tools
-> Real-time collaboration tools share documents, programs, video, audio conferencing, and projects. Technologies include Trello, Slack, Google Docs, and many more.
-> These facilities are designed for sharing content, revisions, and messages pertaining to the shared materials. Thanks to Node’s event-based architecture and asynchronous functionality, users can make changes and convey updated information to the team.
-> It updates the collaboration environment quickly, ensuring that every user sees the same, consistent application representation. Additionally, push alerts alerting the user to changes are provided for every modification.

# Internet of Things
-> The Internet of Things, sometimes known as IoT, is a cutting-edge technology that integrates smart sensors on devices to process and carry out requests. It can be difficult to manage requests and data flow from and amongst IoT devices because there could be hundreds of them.
-> IoT systems can process several concurrent requests and events sent by hundreds or even millions of devices on the network thanks to node.js’s asynchronous functionality without experiencing a slowdown in speed or performance.
-> Multiple queries and data streaming from IoT devices don’t slow down Node.js servers since asynchronous processing is suitable for I/O-intensive jobs on IoT networks. Node.js is speedy when acting as an application layer between these devices and the databases that store their data.


# How to Use Node JS?
The installer package available on the NodeJS official website makes the installation of NodeJS and NPM simple.

* Developers can download the NodeJS WebSite installation.
* Activate the installation.
* After agreeing to the license agreement and completing the installer’s stages, click the next button.
* Restart your computer or system.

Try out NodeJS now by printing its version with the command shown below:

> node -v

Then, check npm by using the command to output its version.

> npm -v

Create a sample.js file after installation, and then use the following command to launch the sample.js file to see if node.js is indeed functioning.

> node sample.js

If you get the output, then the node.js installation is complete.

Developers should download Node Package Manager (NPM), included by default with every node.js download.

NPM is a package module that aids in efficiently loading dependencies for javascript developers. Developers can use the npm CLI tool to retrieve the whole list of packaged modules on the npm website, which comes pre-installed with Node.js.

Several helpful npm modules include:

express 
mongodb 
socket.io 
connect 
forever


