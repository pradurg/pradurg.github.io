---
layout: page
title: ργαδμγg | Kirtimukh
permalink: /projects/kirtimukh/
---

## Introduction
As a part of constant efforts towards Stability & Reliability, what every Software Engineer look for is High Precisions & Predictability. Especially when margin for errors & recovery gets tinier.

## Why does Fault Tolerance/Resiliency matter?
### Imagine...
* You are in an overloaded elevator, which keeps returning to the ground floor in an honest attempt to lift entire load
* Everytime you turned on Air Conditioner & Television, it results in power-cut in your entire area
* A Civil Engineer receiving a call in the middle of the night that flood gates have opened unexpectedly
* You are mid-air and flight's landing gears appear to have jammed because all passengers are watching movies

##### As an engineer, we all do understand that systems can give-up or fail anytime and they might need regular servicing/tuning.
#### However _the experience is frustrating_ as well as scary at the same time, isn't it?

## Resiliency & Microservices
Resiliency is the key thing to look after in Microservices Architecture.
### Circuit Breaker
One of the most important or moreover the critical/key aspects of Microservices Architecture is fault tolerance using Circuit Breakers.
One may choose between FailFast or FailSafe approaches, purely depends on the use-cases.
While the FailFast approach effectively provides fast failing, faster recovery & effectively better utilisation of resources, FailSafe approach tolerates fluctuations.

### Throttling
While most of the Architectures rely completely on Circuit Breaker Pattern & Retries, which gives the complete control of _The Stability_ to the client side.
They do perform well initially in the small setup or closely working small number of microservices.
As organisations grow bigger & bigger, clients may not have fine-tuned parameters, resulting in creating back-pressures.
##### And then comes those _completely eventful_ moments when in the event of _Outages due to Back Pressure_, we end up searching for _which client_ caused this.
Throttling essentially provides a mechanism for the flow control in the event of unexpected increase in incoming traffic or increase in latencies from downstream.

## About Durg | Kirtimukh
##### _Durg_ means _Fortress_ or something difficult to conquer.

### About Kirtimukh
##### _Kirtimukh_ is the guardian of the thresholds.


[![Google Slides][Img-Presentation]][Link-Presentation]

[Link-Presentation]: https://docs.google.com/presentation/d/1vAA3PAlr31qwCG--vBX4hD2YIHjqtWRsZPHWDPB7jkk/edit?usp=sharing
[Img-Presentation]: https://raw.githubusercontent.com/pradurg/kirtimukh/develop/docs/img/presentation.png
