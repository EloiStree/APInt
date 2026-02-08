
# APInt

> APInt is a concept for playing games by sending and receiving integers over a shared network for remote control through APIs.

My personal use of it is to teach coding by playing games on several computers and through code tournaments.   
But it can be used for much, much more.   

Coming from the concept of **cloud variables** in Scratch and my need for remote control over several computers for botting (in a white-hat philosophy), I arrived at a concept close to IFTTT:   
a mutualized Raspberry Pi host that only accepts integers and redistributes them to listeners.  
  
By creating conventions and APIs using only integers, it allows a simple, manageable scope for a single developer like me.   

Creating an HTTPS and secure server can be a pain, but it is required to pass through firewalls and school security.   
That is why I designed my code to be mutualized, using authentication based on ECC and RSA.   

I am building two convention around this tool:
- IID: Index Integer Date ([📖](https://github.com/EloiStree/IID))
- S2W: Scratch 2 Warcraft ([📖](https://github.com/EloiStree/S2W)) 

## APInt
  
* **As a Raspberry Pi**: a mutualized server   
* **As a toolbox**: integer tools for transporting and using integers   
* **As an app store app**: a remote control hub in Godot with built-in macros and input tools   

**APInt.io** = API + INT + In/Out   
But also from *a pint* 🍻, because it is under the [Beerware license](https://fr.wikipedia.org/wiki/Beerware).   
Well… technically, the [Pizza License](https://github.com/EloiStree/license).   
[https://github.com/EloiStree/license](https://github.com/EloiStree/license)   

Hope you like it,
**Eloi Stree**


-------------------------


## **What I am building concretely**

* A Raspberry Pi program that hosts a server allowing the sending and receiving of integers outside of tournaments.
* A variant of the Raspberry Pi program with scheduling and encrypted connections, intended to create tournaments.
* A Godot application and a Python console app that allow connection via an encrypted key and can be used as a local gateway.
* A bit of Flask website on Pi for Javascript and developer that want to participate ([📖](https://github.com/EloiStree/apint.io)).
* A Twitch and Discord bot with encrypted connections through chat, intended to remotely control systems using integers. Yes, from your bed.

## **Goal**

The goal is to create coding tournaments with automatic player pooling based on RSA/ECC, synchronized at NTP UTC time.

## **Gate application availability**

The gateway application will be available on:

* Python: *To be added later*
* Android: *To be added later*
* Quest: *To be added later*
* Steam Frame: *To be added later*
* Steam: *To be added later*
* Godot packages: *To be added later*
* Unity packages: *To be added later*
* Pi-App: *To be added later*
* Steam Deck Store: *To be added later*


## **Publish Schedule**

* Every **12 July** for a coding tournament during my birthday.
* Every **last weekend of January** for the Global Game Jam.
* Every **0-hour game jam** around **November**.

### **Major Event**

* The big one: **12 July 2029**. I want to organize a large tournament for my 40th birthday.



---------

Note: I should look at the Steam Remote Play:      
- https://partner.steamgames.com/doc/features/remoteplay     
- https://partner.steamgames.com/doc/features/steam_controller  
If you know who to implement it, feel free to ping me.    
    
