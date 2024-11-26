**Building a simple Voting App using Kubernetes 
This repository contains the resource Manifests for a simple Voting App that is built using  Kubernetes. This Voting App is a simple web application that allows users to Vote for their favorite pets.

Architecture Overview 
The Voting App consists of the following components:

A Frontend Service that serves the web application to users to vote for their favorite pets (cats or dogs). It is Developed using Python Flask.
A Redis Service that stores the votes.
A Worker Service that processes the votes and stores them in the Postgres databas. It is Written in .NET.
A Postgres Service that stores the details of the votes such as the pet name and the number of votes.
A Result Service that displays the results of the votes. It is Written in Node.js.
