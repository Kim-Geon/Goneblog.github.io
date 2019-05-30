---
layout: post

#event information
title:  "Visual Studio Code Python 설치"
cover: "img/blur-background-1680x1050-spectrum-electromagnetic-4k-901-1.jpg"
date:   2019-05-30

#event organiser details
organiser: "Lucas Gatsas"


---
<h2 class="section-heading"> Visual Studio Code Python 설치</h2>


First: Make sure your App is running on Localhost <code>port:80</code>


Seconds: Clone Tilda : <a href="https://www.npmjs.com/package/tilda">Tilda</a>


Thrid: Create a<code>cli.js</code> file and inpust the following Code below

<div style="overflow:auto; height=200; width=100%;">
<pre style="color:black;background:white;"><pre>

// Make sure that no matter where we call the command from,
// we lift the app that lives in the same directory as this script
process.chdir(__dirname);
// Get an instance of Sails
var sails = require('sails');
// Lift the Sails app in the current working directory
       console.log("Start The GITLIST App");
        console.log("To see your app. visit:");
        console.log(clc.xterm(39).bgBlack.underline('http://127..0.0.1'));
        console.log("To Clone the Repository and Open Source:");
        console.log(clc.xterm(39).bgBlack.underline('see: http://www.github.com/spaceg/github.io'));
        console.log("Bash The Universe by Hello World");
        console.log("©.2016 by Gitlist OS");

        console.log("press c to stop the app");


sails.lift({log:{noShip: true}});

/*  sails.lift(rc('sails'));*/

</pre></pre></div>
