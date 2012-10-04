Scissors and Glue for Processing
================================

*Scissors* and *Glue* are message building and parsing classes for use in [Processing](http://processing.org/).

These versions can be used to pass messages between processing sketches over networks OR locally between a processing sketch and a locally connected [Arduino](http://arduino.cc).

As these classes are not at this time packaged into a library (that's coming, want to help?) you can add them by simple dropping the Scissors.pde or Glue.pde files onto existing sketches. 

Glue for Processing
-------------------

Glue assembles MESSAGES into easily parsed PACKAGES.  Individual message ELEMENTS can be quickly joined together and then extracted with Scissors (below).  The ELEMENTS can be integers, floats or Strings and mixed type messages are allowed.  The first ELEMENT is given index = 0 (zero).  ELEMENTs are appended to the current MESSAGE and the index increments automatically each time.   GLUE takes care of type and indexing for you.  

Processing GLUE is currently just a CLASS, drop it on your open sketch or use Processing's Sketch-->Add File...  menu.



Scissors for Processing
-----------------------

Scissors parse messaged packed with Glue.  MESSAGES must be packed with GLUE or follow the GLUE structure.   ELEMENTS are extracted by index and can be accessed out of order.  To retrieve an ELEMENT, you must know its index and type ( integers, floats or Strings ).  

Processing SCISSORS currently just a CLASS, drop it on your open sketch or use Processing's Sketch--> Add File... menu.  


Full documentation coming very soon -- in the mean time look at readme.md files distributed with Arduino Scissors and Glue below.



Arduino Scissors and Glue
=========================

You can also get *Arduino* versions of **Scissors** and **Glue**.

[Arduino Scissors](https://github.com/hex705/Scissors)


[Arduino Glue](https://github.com/hex705/Glue)








