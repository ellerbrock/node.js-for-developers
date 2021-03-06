![logo](https://github.frapsoft.com/top/nodejs-logo.png)

# Node.js for Developers [![Build Status](https://travis-ci.org/ellerbrock/nodejs-for-webdeveloper.svg?branch=master)](https://travis-ci.org/ellerbrock/nodejs-for-webdeveloper) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/) [![Gitter Chat](https://badges.gitter.im/frapsoft/frapsoft.svg)](https://gitter.im/frapsoft/frapsoft/)

Full Stack Javascript Development with [Node.js](https://nodejs.org/en/)

## Recommended Reading

-   [Unix Philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs)
-   [Writing small & reusable Modules](http://substack.net/how_I_write_modules)
-   [Awesome NPM](https://github.com/sindresorhus/awesome-npm)
-   [Awesome Node.js](https://github.com/sindresorhus/awesome-nodejs)
-   [Awesome TypeScript](https://github.com/ellerbrock/awesome-typescript)
-   [The Art of Node](https://github.com/maxogden/art-of-node#modules)
-   [Node School](http://nodeschool.io/)
-   [NPM Developer Guide](https://docs.npmjs.com/misc/developers)
-   [Common.js Module Specs](http://www.commonjs.org/specs/modules/1.0/)
-   [Getting Started with Node and NPM](https://github.com/Microsoft/nodejs-guidelines/blob/master/getting-started.md)
-   [Interactive Guide for exploring package.json](http://browsenpm.org/package.json)
-   [10 Cool Things You Probably didn't realize npm could do](http://blog.izs.me/post/1675072029/10-cool-things-you-probably-didnt-realize-npm-could-do)
-   [Semantic Versioning](http://semver.org/)
-   [Semantic Versioning & Node.js](https://nodesource.com/blog/semver-a-primer/)
-   [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Quick Intro to Core Features
-   [Node.js for Developers](https://github.com/ellerbrock/node.js-for-developers) - Guide for Node.js Developers

## Modules

-   [Publishing NPM Packages for Developers](https://github.com/ellerbrock/tutorial-publishing-npm-packages)
-   [Choosing a licence for your Open Source Project](https://github.com/ellerbrock/tutorial-choosing-open-source-licence)
-   [Node.js Modules Documentation](https://nodejs.org/api/modules.html)
-   [Node.js Module Pattern - simple examples](https://darrenderidder.github.io/talks/ModulePatterns/)
-   [Understanding module.exports and exports in Node.js](https://www.sitepoint.com/understanding-module-exports-exports-node-js/)
-   [An overview of Node: Modules and npm](http://book.mixu.net/node/ch8.html)
-   [Creating and Publishing a Node.js Module](https://quickleft.com/blog/creating-and-publishing-a-node-js-module/)
-   [Creating Node.js modules](https://docs.npmjs.com/getting-started/creating-node-modules)
-   [How to write Node.js Modules](http://www.hacksparrow.com/how-to-write-node-js-modules.html)
-   [Modules 1.1 Wikipedia](http://wiki.commonjs.org/wiki/Modules/1.1)

#### Simple Module Example

index.js:

    const pkg = require("./package.json");

    module.exports = () => pkg;

run.js:

    const pkg = require("./index");

    console.log('Name: ' + pkg().name + ' Version: ' + pkg().version);

## Asynchronous Javascript

#### Promises

-   [MDN Promises](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Promise)
-   [Promises in Node.js with Q – An Alternative to Callbacks](https://strongloop.com/strongblog/promises-in-node-js-with-q-an-alternative-to-callbacks/)
-   [JavaScript Promise API](https://davidwalsh.name/promises)
-   [Awesome Promises](https://github.com/wbinnssmith/awesome-promises)
-   [Bluebird.js](http://bluebirdjs.com/docs/getting-started.html)

#### Callbacks

-   [Callbacks MDN](https://developer.mozilla.org/en-US/docs/Mozilla/js-ctypes/Using_js-ctypes/Declaring_and_Using_Callbacks)
-   [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/README.md#you-dont-know-js-async--performance)

## Frameworks

-   [Node.js Framework Overview](http://nodeframework.com/) - Hand-picked registry of Node.js frameworks.
-   [Koa](http://koajs.com) - A new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
-   [Express](http://expressjs.com) - A minimal and flexible web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
-   [Feathers](http://feathersjs.com) - A minimal and flexible microservice framework built in the spirit of Express.
-   [Hapi](http://hapijs.com) - A rich framework for building applications and services.
-   [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
-   [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. _(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))_
-   [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
-   [Restify](http://restify.com) - A node framework built specifically to enable you to build correct REST web services.
-   [Interfake](https://github.com/basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node.js, command-line and HTTP interface.
-   [Derby](https://github.com/derbyjs/derby) - MVC framework, making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
-   [Restberry](http://restberry.com) - Framework for setting up RESTful JSON APIs, applied to your database models without needing to write any code.
-   [Catberry](http://catberry.org) - Framework with Flux architecture, isomorphic web-components, and progressive rendering.
-   [ThinkJS](https://thinkjs.org) - Framework with ES2015+ support, WebSockets, REST API.

## Flat File CMS

-   [Hexo](https://hexo.io/) - A fast, simple & powerful blog framework
-   [Raneto](http://raneto.com/) - Markdown powered Knowledgebase for Nodejs
-   [MetalSmith](http://www.metalsmith.io/) - An extremely simple, pluggable static site generator.
-   [WinterSmith](http://wintersmith.io/) - Flexible, minimalistic, multi-platform static site generator built on top of node.js.

## Blog Systems

-   [Ghost](https://ghost.org/) - Open Source Blogging Platform.

## Debugging

-   [atom-node-debugger](https://github.com/kiddkai/atom-node-debugger) - Debugger for Atom
-   [iron-node](https://github.com/s-a/iron-node) - Debug your Code with Chrome Developer Tools.
-   [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools
-   [node](https://nodejs.org/api/debugger.html) - Node's build in Debugger Utility
-   [Vorlon.js](http://www.vorlonjs.com/) - Remotely debugging and testing your JavaScript

#### Examples:

_node-inspector_

`npm install -g node-inspector`  - install global  
`node-debug --debug-brk index.js` - starts debugging and stop in first line  
`debugger` - inside the script write debuggger to set a breakpoint. also its possible inside the debugger window to set breakpoints by clicking in the line.

## Dependencies

-   [david](https://github.com/alanshaw/david) - Node.js module that tells you when your package npm dependencies are out of date.

## Time Safer

-   [live-server](https://github.com/tapio/live-server) - A simple development http server with live reload capability.

## Security

-   [Node.js Security Tutorial](https://blog.risingstack.com/node-hero-node-js-security-tutorial/) - Howto defend your applications against the most common attack vectors.
-   [Node.js Security Checklist](https://blog.risingstack.com/node-js-security-checklist/)
-   [Node.js Security Tips](https://blog.risingstack.com/node-js-security-tips/)
-   [nsp](https://nodesecurity.io/opensource) - Command line interface to the Node Security Platform.
-   [http authentication](https://github.com/request/request#http-authentication)

## Language Support

-   [ES6 Support](https://nodejs.org/en/docs/es6/) - Node ECMAScript 2015 (ES6) Support and beyond
-   [Node Releases](https://nodejs.org/en/download/current/) - Download Site for the different Node Versions
-   [Node with Babel](https://babeljs.io/docs/setup/#installation) - How to use Babel with Node  
-   [node.green](http://node.green/) - Lists of the current ES2015 JS Support for the different Note Versions

## Travis CI

-   [Building a Node.js project](https://docs.travis-ci.com/user/languages/javascript-with-nodejs)
-   [validate your .travis.yaml](http://yaml.travis-ci.org/)

## Semantic Version Examples

-   ~1.2.3 installs all the patches (>=1.2.3 &lt;1.3.0)
-   ^1.5.1 installs patch and minor versions (>=1.5.1 &lt;2.0.0)

## Docker Images

#### official Node.js

-   `docker pull node` - [official Node.js](https://hub.docker.com/_/node/)

#### NodeOs

-   `docker pull nodeos/nodeos` - [official NodeOS](https://hub.docker.com/r/nodeos/nodeos/)

#### Flat File CMS

-   `docker pull gugu/raneto` - [Raneto](https://hub.docker.com/r/gugu/raneto/)

#### Blog

-   `docker pull ghost` - [official ghost](https://hub.docker.com/_/ghost/)

#### NoSQL

-   `docker pull mongo` - [official MongoDB](https://hub.docker.com/_/mongo/)
-   `docker pull redis` - [official Redis](https://hub.docker.com/_/redis/)


### Contact / Social Media

*Get the latest News about Web Development, Open Source, Tooling, Server & Security*

[![Twitter](https://github.frapsoft.com/social/twitter.png)](https://twitter.com/frapsoft/)[![Facebook](https://github.frapsoft.com/social/facebook.png)](https://www.facebook.com/frapsoft/)[![Google+](https://github.frapsoft.com/social/google-plus.png)](https://plus.google.com/116540931335841862774)[![Gitter](https://github.frapsoft.com/social/gitter.png)](https://gitter.im/frapsoft/frapsoft/)[![Github](https://github.frapsoft.com/social/github.png)](https://github.com/ellerbrock/)

### Development by

Developer / Author: [Maik Ellerbrock](https://github.com/ellerbrock/)  
Company: [Frapsoft](https://github.com/frapsoft/)

### License 

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />

This work by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/ellerbrock/" property="cc:attributionName" rel="cc:attributionURL">Maik Ellerbrock</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.