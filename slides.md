![GeneralAssemb.ly](assets/ga.png "GeneralAssemb.ly")

##Building Delightful Apps with Ruby on Rails
###Hubert Lee

---

##Introductions!

* Your name
* What you do
* What you hope to get out of this workshop

---

##Agenda

* What is web development?
* Ruby on Rails
* The command line
* Our first Rails app

* Please feel free to ask questions at any time!

---

##Web Development

* What does web development mean to you?

---

##Web Development
###Back-end vs Front-end Development

Let's define a few terms:

* _Web Development_ <span class="fragment" data-fragment-index="1"> - building applications available on the web</span>
* _Front-End Development_ <span class="fragment" data-fragment-index="2"> - client / browser code (HTML, CSS, JavaScript)</span>
* _Back-End Development_ <span class="fragment" data-fragment-index="3"> - server-side code (Ruby, C#.NET, Java)</span>

---

##Web Development
###How the internet works

* To understand Ruby on Rails we need to understand the internet

---

![GeneralAssemb.ly](assets/Exercise_icon_md.png)
##Draw The Internet

Time: 7 minutes

1. Grab a whiteboard marker
2. Draw a diagram that represents your understanding of how the Internet works. Here are some questions to consider as you draw:
  * What happens when you hit enter on your address bar?
  * Where does a website live?
  * What does a webserver need to do in order to respond to your request?
3. Share with the rest of the class and let's discuss

---

##Web Development
###How the internet works

![](assets/server-side.jpg)

---

##Ruby on Rails
###Background

Ruby on Rails is an open source web framework written in the Ruby programming
language.

Created by David Heinemeier Hansson (@dhh) in 2004 as a spinoff of the reusable
components of [Basecamp](https://basecamp.com/).

---

##Ruby on Rails
###Framework

Ruby on Rails is a framework for building websites.

It provides solutions to the most common problems faced when building websites.

* Routing
* Templating
* Database abstraction
* And more!

---

##Ruby on Rails
###Websites built on Rails

* Twitter
* Airbnb
* Groupon
* Shopify
* Beecrazy
* General Assembly

See more [here](http://www.developerdrive.com/2011/09/20-best-sites-built-with-ruby-on-rails/)

---

##Rails & My Browser
###The request/response cycle

* HTTP (the protocol that drives the Web) communicates via input/output just like the terminal.

* Browsers send a request (the input) and the server returns a response (the output).

![Request Response Diagram](assets/response_request.png)

---

##Recap
###Make an app

```bash
$ rails new my_app_name
$ cd my_app_name
```

---

##Recap
###Create the database tables

```bash
$ rake db:migrate
```

---

##Recap
###Start the server

```bash
$ rails s
```

* Go to [http://localhost:3000](http://localhost:3000) in a browser

---

##Recap
###Generators

```bash
$ rails generate model Book author:string title:string abstract:text
$ rails generate model Shelf category:string
$ rails generate controller books
```

* Generators provide the bare necessities for adding a resource or model to your Rails app

---

![GeneralAssemb.ly](assets/Code_along_icon_md.png)
##Hosting Public Files
###Rails can be a simple file server too!

Add a static file to the `public` folder.

* Create the file `public/hello.html`
* Start your server with `rails s`
* Visit [http://localhost:3000/hello.html](http://localhost:3000/hello.html)

---

##Working Like a Developer

* Leverage the online community's vast libraries and documentation (Google is your best friend)
* Share the knowledge you gain and give back to the community when you can
* Take pride and joy in what you work on
* Be efficient:
  * Use the keyboard and shortcut keys as much as possible
  * If you find yourself doing the same thing repeatedly, automate it

---

##The OS and the File System

---

##The Command Line
###What is it?

The command line is a terminal giving you direct access to your operating system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as committing our code) are best performed in the command line.

---

##The Command Line
###How do I start?

For Macs:

* Open the "Terminal" app
* For a better experience, download and install "iTerm 2", which is a replacement app that is slightly better.


For Windows:

* Open the "Command Prompt" application
* For a better experience, try "Console2" (http://sourceforge.net/projects/console/)

---

##The Command Line
###Why are we using it?

* In order to learn Ruby without Rails, we must learn how to run Ruby programs on their own.
* To do so, we can simply create "stand-alone" Ruby applications.
* A stand-alone Ruby app consists of one or more Ruby files (files that have a .rb extension)
* Once you have written a Ruby file, you can run the file by typing:
  * ```ruby file.rb``` (this would run a Ruby file named file.rb)
* This is the basis of how we will be writing and testing our Ruby applications in the initial portion of this course

---

![GeneralAssemb.ly](assets/Code_along_icon_md.png)
##Command Line Basics

---

![GeneralAssemb.ly](assets/Exercise_icon_md.png)
##Command Line Basics Exercise

---

##QUIZ
1. How do you change directories using the command line?
2. What is Git and GitHub?
3. How do you add files to git?
4. What is a GitHub repository?
5. What is the correct way to push changes to your GitHub repo?

    a. `git pull origin master`

    b. `git commit -m "push to GitHub"`

    c. `git push origin master`

---

##Ruby
###A programming language

* An open source programming language
* Easy to read and natural to write
* Created by Yukihiro Matsumoto (aka Matz) with the goal of building a language FOR developers
* Regularly maintained and evolved (recently reached version 2.1)

<div style="text-align:center;">
  ![](assets/02/ruby_img.png)
</div>

---

##Rails
###A web application framework

* Open source web application framework that is built in Ruby
* Allows you to create interactive web applications that query a database
* Created by David Heinemer Hansson (DHH) to simplify the task of building web applications, emphasizing _convention over configuration_

<div style="text-align:center;">
  <img src="assets/02/dhh.jpg" style="margin-right:20px;"/>
  ![](assets/02/rails.png)
</div>

---

##Ruby & Rails
###Ruby first.

* It will be easier to navigate a Rails project once we have a basic understanding of Ruby.
* We will first teach you how to write simple Ruby scripts as stand-alone applications
* Once we have become familiarized with Ruby, we will start building Rails applications (which are essentially groups of Ruby script files that work together)

---

##Computational Thinking
###What does it mean to program?

> Learning about "for" loops is not learning to program, any more than learning about pencils is learning to draw.
>
>  -Bret Victor, Learnable Programming

---

![GeneralAssemb.ly](assets/Code_along_icon_md.png)
##Designing Algorithms:
###Paper airplane

---

##Designing Algorithms
###It's about how you think
* Figure out how to solve a problem manually
* Break down the solution into small, incremental steps
* Translate each step into code

> Everything must be made as simple as possible, but no simpler.

