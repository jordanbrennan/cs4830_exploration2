# CS4830 - Exploration 2
##### *Exploration of MEAN stack for senior web development class at Mizzou*

This is part 2 of my continuing series of projects for a web development class I'm in.  Yet again, I'm trying out a technology in which I'm a complete greenhorn! :smiley: Lately, I've been super interested in server-side Javascript.  I’ve got some experience with client-side Javascript, but I’ve never worked with Node.js or anything server side.  So, I thought for this exploration I’d delve into full-stack Javascript, specifically the MEAN stack...

MEAN stack =
- MongoDB (and the optional MongooseJS) : JSON NoSQL database
- Express.js : the de facto node.js web app server framework
- AngularJS : Google's client-side MVC framework for SPAs
- Node.js : javascript runtime environment for developing server-side webapps

I have almost no real experience with any of these technologies/frameworks, so this exploration was a lot of reading documentation and learning about full-stack Javascript before I dive in and try to build something cool.

####Overall MEAN Resources:
- two popular (and very similar) open-source options: http://mean.io/#!/ (original), and http://meanjs.org (fork from the original)
    - difference between the above two: http://www.creativeworkline.com/2014/05/meanio-vs-meanjs-comparison/ and http://stackoverflow.com/questions/23199392/difference-between-mean-js-and-mean-io and http://blog.meanjs.org/post/76726660228/forking-out-of-an-open-source-conflict
- wikipedia overview: https://en.wikipedia.org/wiki/MEAN_(software_bundle)
- some thoughts on full-stack Javascript: http://www.toptal.com/javascript/guide-to-full-stack-javascript-initjs
- install/setup/tutorials:
    - https://thecodebarbarian.wordpress.com/2013/07/22/introduction-to-the-mean-stack-part-one-setting-up-your-tools/
    - https://masteringmean.com
    - https://www.mongodb.com/blog/post/building-your-first-application-mongodb-creating-rest-api-using-mean-stack-part-1?_ga=1.134664369.1790217559.1443324993
    - https://hackhands.com/how-to-get-started-on-the-mean-stack/
    - https://thinkster.io/mean-stack-tutorial

####Resources for MongoDB + MongooseJS :
-  official site + docs : https://www.mongodb.org
- installing Mongo on Ubuntu: https://docs.mongodb.org/getting-started/shell/tutorial/install-mongodb-on-ubuntu/
- Mongo w/ MEAN from a MongoDB engineer’s perspective: http://blog.mongodb.org/post/49262866911/the-mean-stack-mongodb-expressjs-angularjs-and
- Integrating Mongo w/ Node.js: http://docs.mongodb.org/ecosystem/drivers/node-js/?_ga=1.231725919.1790217559.1443324993
- Mongoose.js : http://mongoosejs.com

####Resources for Express.js :
- official site + docs: http://expressjs.com + https://github.com/expressjs
- overview: https://en.wikipedia.org/wiki/Express.js
- tutorials / getting started:
    - http://evanhahn.com/understanding-express/
    - https://www.codeschool.com/courses/building-blocks-of-express-js (first part is free I think)
- might also look into connect.js: https://github.com/senchalabs/connect#readme

####Resources for AngularJS :
- official site: https://angularjs.org
- overview: https://en.wikipedia.org/wiki/AngularJS
- tutorials:
    - http://www.toptal.com/angular-js/a-step-by-step-guide-to-your-first-angularjs-app
    - http://www.w3schools.com/angular/
    - https://www.codecademy.com/en/courses/learn-angularjs
    - https://egghead.io/technologies/angularjs (price?)
- maybe also look at http://backbonejs.org and http://emberjs.com
- Cool comparison of various JavaScript frameworks/libraries for single-page and rich JavaScript apps: http://blog.stevensanderson.com/2012/08/01/rich-javascript-applications-the-seven-frameworks-throne-of-js-2012/ + also check out http://todomvc.com

####Resources for Node.js :
- official site + api docs: https://nodejs.org/api/
- installing node on Ubuntu: https://github.com/nodesource/distributions#installation-instructions
- lots of good info: https://en.wikipedia.org/wiki/Node.js
- a nice beginner's guide: http://blog.modulus.io/absolute-beginners-guide-to-nodejs
- an intro to node.js: http://hectorcorrea.com/#/blog/introduction-to-node-js/51
- pros/cons + when to use node.js: http://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js
- event loop in node.js: https://developer.yahoo.com/blogs/ydn/part-1-understanding-event-loops-writing-great-code-11401.html

####So let’s get our hands dirty...
I decided to dive in to MEAN with a pre-built Azure MEAN stack on an Ubuntu VM (later, if there’s time, I’ll get some practice installing each piece separately on a blank Ubuntu machine, but I wanted to get something up and running quickly). Azure’s MEAN option uses a Bitnami stack; the following links were helpful.
- https://bitnami.com/stack/mean
- https://wiki.bitnami.com/Azure_Cloud/Getting_Started
- https://wiki.bitnami.com/Infrastructure_Stacks/BitNami_MEAN_Stack
- https://community.bitnami.com/c/mean

I’m currently working on building my own app with MEAN, but right now I’ve only got the default site up, which you can find here: http://batman-t644d6o5.cloudapp.net .  
I'll try to update this repo whenever I make progress on the app.

####Recap:
Even though I’m still a complete newbie with Node and the MEAN stack, I’m very excited to keep playing with it.  It seems to be a very powerful, flexible, and scalable set of tools for building web apps.  I’ll definitely be experimenting more with it in the future...

####Other potentially worthwhile Javascript research:
- other JavaScript frameworks like sails.js, hackathon starter, clever stack, etc...
- mocha.js and chai.js for testing and development processes
- grunt.js for build processes
- RequireJS and CoverJS
- PhantomJS for indexing and SEO of SPAs: https://vickev.com/#!/article/easily-index-your-single-page-application-thanks-to-phantomjs
