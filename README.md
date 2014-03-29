TidalChat
=========

TidalChat is a very simple realtime web application on a [Pharo](http://www.pharo-project.org/home) backend and [Amber](http://amber-lang.net/) frontend stack.

##Motivation
There are *many*  very good stacks for doing this kind of applications. This is a Smalltalk based one. If you already know Smalltalk have fun, if you don't know it yet this might give you an idea of how empowering it can be for a developer.

##Applicability
Learn / teach yourself or show in workshops.

###Loading

Use this snippet to load it into a fresh [Pharo](http://www.pharo-project.org/home)* image:

    Gofer it 
		smalltalkhubUser: 'sebastianconcept'
		project: 'TidalChat'; 
		package: 'ConfigurationOfTidalChat';
		load.
	
    (Smalltalk at: #ConfigurationOfTidalChat) load

###Examples

Use this to start and stop [Zinc](http://zn.stfx.eu/zn/index.html) http server in a Pharo workspace:

    TDServer startOn: 4001.    TDServer stop. 

exaplain some more...

    code...
 

###Contributions

...are welcomed, send that push request and hopefully we can review it together

###*Pharo Smalltalk
Getting a fresh Pharo Smalltalk image and its virtual machine is as easy as running in your terminal:
 
    wget -O- get.pharo.org/30+vm | bash

_______

MIT - License

2014 - [sebastian](http://about.me/sebastianconcept)

o/