remdis
======

Scala project for distributing self contained jar based tasks to remote workers using scala-actors (not Akka).

Status: *alpha*

This project was created to serve as a map-reduce manager for the navier-stokes project.

Getting started
-------------------
To start a coordinator:

    mvn scala:run 
    
To start a worker:

    mvn scala:run -Dclass=Worker
