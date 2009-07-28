SGHotKeyLib - Hot Keys For Mac OS X Leopard and beyond
=========================

* Maintained by [Justin Williams](http://carpeaqua.com)
* Originally by Quentin D. Carnicelli

What is SGHotKeyLib?
==================

SGHotKeysLib is a fork of Quentin D. Carnicelli's excellent [PTHotKeysLib](http://rogueamoeba.com/sources/) library for registering shortcut keys on Mac OS X.

PTHotKeysLib has served us well for many years, but as I was working on upgrading my applications to run natively in 64 bit I was running into issues.  The original code itself used many deprecated methods, used 32 bit intger types, etc.  As I fixed those issues, my OCD started to get the best of me and I started reformatting and rewriting portions of the code using modern Objective-C practices and paradigms.  

SGHotKeysLib does the following:

* Adopts Objective-C 2.0 syntax, properties and other language features (suck it dot syntax haters)
* Uses Leopard's Text Input Sources (no patching required)
* Runs natively in 64 bit
* Requires Garbage Collection
* Removes legacy code support (no more checking for 10.1, no more Project Builder)
* Cleans up the code formatting & variable declarations
* Puts the code on Github for hot forking action

What's in the box?
==================

SGHotKeysLib includes:

* The SGHotKeySLib itself 
* A sample application that demonstrates how it works.  

The sample uses a custom-built version of the [ShortcutRecorder](http://code.google.com/p/shortcutrecorder/) framework to demonstrate setting a hot key.  

Help Me!
==================

SGHotKeysLib is a modernization of a piece of code many of us have been using for several years, and I'm sure it could be improved even more.  If you have ideas for how to do that, please fork away. 