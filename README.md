Boris Bikes
===========

A program that will run all the Boris Bikes Docking Stations, simulate all the 
Bikes, and emulate all the infrastructure (vans, repair staff, and so on). 

User stories

```
As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

As a person,
So that I can use a good bike,
I'd like to see if a bike works
```

Nouns
-----

* Person
* Bike
* DockingStation

Verbs
-----

* use
* release
* see\_if\_works

Objects        | Messages
-------------- | -------------
Person         | 
Bike           | see\_if\_works, use
DockingStation | release

Diagram
-------

Bike <-- use
Bike <-- works? --> true/false
DockingStation <-- release_bike --> a Bike