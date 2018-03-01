- title : Rise of ASP.NET Core
- description : 
- author : Jarosław Krefta, Paweł Jeliński
- theme : night
- transition : default

***

##Rise of ASP.NET Core
<br/>
<br/>
Jarosław Krefta<br/>
Paweł Jeliński

***

###Who do we work for?

---

![Jet Shop](images/introduction/jetshop.png)

---

###Aka " The Jetson team " :)
![Jetsons Team](images/introduction/jetsons_team.jpg)

***

###Who are we?
![Jetsons Team](images/introduction/drombo.jpg)

***

###Jarosław Krefta

---

###Guess which one I am? :)
![Astro and George](images/introduction/jarek/astro_plus_george.jpg)

---

###Obviously!
![Astruuu](images/introduction/jarek/astruuu.jpg)

***

###Paweł Jeliński

---

###How do I see Myself
![Judge Dreed](images/introduction/pawel/dreed.png)

---

###How teammates see me
![Spanish Inquisition](images/introduction/pawel/spanish_inquisition.jpg)

---

###To be more exact
![Inquisitor](images/introduction/pawel/inquisitor.jpg)

*** 

###What are we not going to talk about
<img alt="Pinky and Brain" src="images/introduction/pinky_and_brain.jpg" class="mh600" />

--- 

###We are not going to sell you anything
###.Net is not a " Golden Hammer "

--- 

###What are we going to talk about
![Spoon](images/introduction/spoon.jpg)

---

###Short history of ASP and friends :)

***  

###Lets go back to ...

***

##It`s 1996 ...

---

###Browsers are at war!
<img alt="Browser wars" src="images/Browser_Wars_(en).png" class="img-white" />

---

###PHP has power equal to potato
<img alt="Potato" src="images/content/potato.jpg" class="mh400 img-white" />

---

###Java just got released and has nothing
<img alt="Java" src="images/content/logos/java.png" class="mh400 img-white" />

---

###ASP CLASSIC gets released
![Asp Classic Logo](images/content/logos/asp_classic.png)

---

####ASP Classic is Microsoft's first server-side script engine for dynamically generated web pages
* Scripting via Virtual Basic (Yes! Not Visual!)
* Addon for IIS
* Supports JScript
* Supports COM modules
* Supports ActiveX(PearlScript)
* Runs on Windows NT 4.0

---
```vb 
<html>
<body>

<%
    Dim x(1,1)
    x(0,0)="Volvo"
    x(0,1)="BMW"
    x(0,2)="Ford"
    x(1,0)="Apple"
    x(1,1)="Orange"
    for i=0 to 1
        response.write("<p>")
        for j=0 to 1
            response.write(x(i,j) & "<br />")
        next
        response.write("</p>")
    next
%>

</body>
</html>
```

---

###Other notable facts
* Release of **IIS 3.0**
* Release of **Internet Explorer 3.0**
* First release of **JScript**
* First release of **ActiveX**

---

####Internet explorer starts getting noticed! (10% of market)
<img alt="IE starter kit" src="images/content/internet-starter-kit.jpg" class="mh500" />

---

###Great Success!
![Great Success!](images/content/reactions/win_internet.jpg)

***

##It`s 1997

---

###New project gets started!

---

###XSP / ASP+
_"We originally called it XSP; and people would always ask what the X stood for. At the time it really didn't stand for anything. XML started with that; XSLT started with that. Everything cool seemed to start with an X, so that's what we originally named it. In the first six months, we didn't use .NET. The CLR didn't exist—it was just starting around the same time we were—so, we were doing most of our prototyping in C++, JavaScript, and ActiveScript script engines. We knew we wanted an object-oriented environment, and we really liked the characteristics a managed programming model provided in terms of garbage collection, nice encapsulation, and object-orientation techniques..._

---

_... We actually started writing production code in C++, though, because at the time we didn't really have a good runtime platform on which to build. We got about two weeks into it when we met up with the CLR team; at the time that team had no partners inside the company building on top of them. The only compiler they had was this thing called "simple managed C," which we affectionately called "smack." We ended up saying, "Maybe we should build on this." It was a huge risk, and at the time our team consisted of three or four people total. We were allowed to take a bet on it mainly because nobody really cared if we failed. Thankfully, we did and it paid off in a huge way. The rest is history, so to speak."_

___Scott Guthrie, co creator of ASP.NET___

---

####There actually was a book on ASP+ released in 2000
![Asp Plus Book](images/content/asp_plus_book.jpg)

---

### Other notable facts

---

###First release of EcmaScript!
![ECMA Logo](images/content/logos/ecma.jpg)

---

###Emergence of new world wide web standard: HTML 4.0
![HTML4 Logo](images/content/logos/html4.png)

---

###Java releases servlets
<img alt="Java" src="images/content/logos/java.png" class="mh400 img-white" />

***

##It`s 1998

---

###ASP CLASSIC 3.0 - last of it`s kind :)
' Last release was in 2000
' Will be supported until 2025

---

###Google is born
![Google](images/content/old_google.png)

---

###Macromedia released Flash 
<img alt="Flash icon" src="images/content/flash/flash_icon.png" class="mh400" />

' Internet exploded with Flash movies and games
' First truly active frontend
' Could not communicate between separate flash clips

---

###Internet after release of Flash
![Omg cat](images/content/reactions/omg_cat.jpg)

---

###Micrsoft after release of Flash
![Mind Blown!](images/content/reactions/mind_blown.jpg)

---

###What Flash promised
![What flash promised](images/content/flash/flash_promise.jpeg)

---

###What Flash delivered
![What flash delivered](images/content/flash/flash_delivered.jpg)

' Required heavy loading
' Did not always run
' Required plugin in browser
' Was abused by community

***

##1999 - 2003

---

###ASP.NET 1.0/1.1 gets released
<img src="images/content/logos/asp_net_1_1.png" class="img-white" />

' Good old ASP in new managed version
' Garbage collector does not impound scaling :)
' This is WebForms
' Same architecture as WinForms
' Event driven architecture
' Upfront and code behind approach to design web application

---

###Cassini. First .net self hosted server
![What flash delivered](images/content/cassini.png)

' Required by .Net 1.0
' Obsolete from .Net 1.1
' Lived until 2008 as a part of VisualStudio
' Modified by community 
 
---

###Internet Explorer has won browser wars!
<img src="images/content/logos/ie6.png" class="img-white" />

---

###Emergence of new world wide web standards:
' World wide web wanted more extensibility

---

###Ajax!
<img src="images/content/ajax.jpg" class="mh600" />

---

###I mean ...
<img src="images/content/logos/ajax.png" class="img-white" />

---

###New HTML standard
![XHTML logo](images/content/logos/xhtml.png)


---

###Pimp my HTML
![Pimp My HTML!](images/content/malczerati.jpg)

***

##It`s 2004

---

### Notable Microsoft releases

---

###There is literaly nothing from Microsoft
![Where is everyone!?](images/content/Travolta2.gif)

***

##It`s 2005

---

###Microsoft realizes that they need to get their "stuff" together
![Turtle vs Rabbit!](images/content/turtle_rabit.jpg)

---

###So to make it up to web developers ...

---

###ASP.NET 2.0 gets released!
* Full support of ECMA standard
* Generic types
* Support for x64 CPU's

' Supports calls from frontend to backend

---

###Problem is ...

---

###Java gets first SpringMVC release!
![SpringMVC!](images/content/logos/spring_mvc.jpg)

---

###PHP gets Cake!
![CakePHP!](images/content/logos/cake_php.jpg)

***

##It`s 2006

---

###ASP.NET 3.0 gets released

' WPF was released
' WCF was released

---

###JQuery reaches version 1.0
![JQuery logo](images/content/logos/jquery.png)

' Frontend revolution
' Allowed for dynamic component rendering
' Encapsulated AJAX calls for all browsers
' Allowed HTML element theming

---

###Flash has reached its end of life
<img alt="Flash icon" src="images/content/flash/flash_icon.png" class="mh400" />

---

###Micrsoft after last release of Flash
![Mind Blown!](images/content/reactions/mind_blown.jpg)

' Microsoft was happy because they ware working on their own version

---

###Flash died! Lets release our own!
![Mind Blown!](images/content/reactions/prise_the_sun.gif)

***

##It`s 2007

---

###SilverLight!
![Oh Yeah!](images/content/reactions/yeah.gif)

---

###Realy?
![Trump](images/content/reactions/trump.jpg)

---

###Why do you release your own Flash!
![Sounds good, does not work!](images/content/reactions/sounds_good_does_not_work.jpg)

' Silverlight was pipeline for in browser execution of .net code
' Used to write sidebar widgets
' Used ActiveX and COM controls
' Desktop like architecture
' Awfully slow
' Example of enterprise integration with legacy

---

###ASP.NET 3.5
###ASP.NET AJAX
###LINQ

---

###MVC CTP is released
####CTP = Current Technology Preview

' CTP - Community Technology Preview
' ASP.NET AJAX standardized handling of ajax calls

---

###Press X to JSON
Added support for JSON to WCF

***

##It`s 2008

---

###Chromium V8 engine
<img alt="V8 Chromium" src="images/content/logos/v8.png" class="img mh400" />

---

###New engine of internet
<img alt="V8 Engine" src="images/content/v8.jpg" class="img mh400" />

***

##It`s 2009

---

###MVC gets released
####It`s only 4 years late!

<img alt="Asp Net MVC logo" src="images/content/logos/asp_net_mvc.png" class="img-white mh500" /> 

---

###Bing is born
![Bane](images/content/logos/bing.jpg)

---

###Meanwhile ...

---

###EcmaScript5 and Node.Js emerges
![Bane](images/content/bane/bane.jpg)

---

![You think internet is your ally!](images/content/bane/bane_internet.jpg)

***

##It`s 2010

---

###Release of ASP.NET 4.0 and WEB PAGES
<img alt="Baman!" src="images/content/bman.jpg" class="w400" /> 

---

###Google releases AngularJs
![Bane holds Batman](images/content/bane/bane_picks_batman.jpg)

---

###Emergence of first full JavaScript stack!

---

####ExpressJs, KnockoutJs, Backbone, Underscore
####AND
####MEAN = MongoDb, ExpressJs, AngularJs, NodeJs

---

<img alt="Bane breaks Batman" src="images/content/bane/bane_breaks_batman.jpg" class="mh500" /> 

***

##It`s 2011

---

###There is nothing from Microsoft
![Where is everyone!?](images/content/Travolta2.gif)

---

###... beside MVC 3 :)

***

##It`s 2012

---

###ASP.NET 4.5 & TPL
![Tasks! Tasks everywhere!](images/content/tasks_tpl.png)

---

###Web Api gets extracted from MVC
![Web Api 2](images/content/logos/asp_net_web_api.png)

***

##It`s 2013

---

###Microsoft releases Chakra engine
![Why do we fall Bruce?](images/content/WhyDoWeFall.gif)

---
###OWIN, Katana and SignalR
![So that we can get up!](images/content/PickUpLie.gif)

---

###Facebook invents React
![React Invented!](images/content/gentelmen.jpg)

***

##It`s 2014

---

![Blue crawl text](images/content/star_wars/galaxy1.png)

---

![Title crawl text](images/content/star_wars/galaxy2.png)

---

![Content crawl text](images/content/star_wars/galaxy3.png)

***

##It`s 2015

---

###ASP.NET Core RC

---

###EcmaScript 6
<img alt="ES6 logo" src="images/content/logos/es6.png" class="img-white" />

---

###Edge
![Edge logo](images/content/logos/edge.jpg)

---

![Facepalm](images/content/reactions/facepalm.jpg)

---

![Triple facepalm](images/content/reactions/triple_facepalm.jpg)

---

- data-background: images/content/bluescreen.png

***

##It`s 2016

---

###ASP.NET Core 1.0
![Asp Net Core 1.0](images/content/logos/dotnetcore.png)

***

##It`s 2017

---

###ASP.Net Core 2.0
![John Cena Super Sayan](images/content/johncena.gif)

***

###Summary

---

https://www.techempower.com/benchmarks/

***

###How can we use this thing?

***

###Web application in 5 min :)

***

###Stack

* React + CerebralJs
* Kestrel + MediatR

***

###Pros and cons

* Pros:
    - decoupling
    - performance
    - easy to extend
    - flexible

* Cons:
    - celebration
    - heavily depends on MediatR and Container

***

###DEMO :)

***

![Tank You!](images/epilogue/tank_you.jpg)

***

###Useful links

* https://stackify.com/what-is-kestrel-web-server/
* https://thefreezeteam.azurewebsites.net/2015/08/10/building-mvc-jimmy-style/
* https://msdn.microsoft.com/en-us/library/bb266332.aspx
* https://www.youtube.com/watch?v=kej3YJDMAW4