---
layout: post
title: Serverless Computing or Function as a Service(FaaS) - Cloud Computing
description: Serverless Computing as a service is a cloud service model which is widely used in today's age and time.
summary: Function-as-a-Service (FaaS) is a serverless way to execute modular pieces of code on the edge. FaaS lets developers write and update a piece of code on the fly, which can then be executed in response to an event, such as a user clicking on an element in a web application. This makes it easy to scale code and is a cost-efficient way to implement microservices.
tags: cloud-computing
pinned: False
minute: 6

---

<b><span style="color:green">FAAS - Function as a Service</span></b><br>

Function-as-a-Service (FaaS) is a serverless way to execute modular pieces of code on the edge. FaaS lets developers write and update a piece of code on the fly, which can then be executed in response to an event, such as a user clicking on an element in a web application. This makes it easy to scale code and is a cost-efficient way to implement microservices.

<span style="color:green">How FAAS works?</span><br>

FaaS gives developers an abstraction for running web applications in response to events, without managing servers. For example, uploading a file could trigger custom code that transcodes the file into a variety of formats.

FaaS infrastructure is usually metered on-demand by the service provider, primarily through an event-driven execution model, so it’s there when you need it but it doesn’t require any server processes to be running constantly in the background, like platform-as-a-service (PaaS) would. 

Modern PaaS solutions offer serverless capabilities as part of common workflows that developers can use to deploy applications, blurring the lines between PaaS and FaaS. 

In reality, entire applications will be composed of a mix of these solutions: functions, microservices, and long running services

<span style="color:green">What are Microservices ?</span><br>

If a web application were a work of visual art, using microservice architecture would be like making the art out of a collection of mosaic tiles. The artist can easily add, replace, and repair one tile at a time. Monolithic architecture would be like painting the entire work on a single piece of canvas.

<center><img src="https://i.imgur.com/4e84fm8.png" style="height:40%; width:80%;"></center><br>

This approach of building an application out of a set of modular components is known as microservice architecture. Dividing an application into microservices is appealing to developers because it means they can create and modify small pieces of code which can be easily implemented into their codebases. This is in contrast to monolithic architecture, in which all the code is interwoven into one large system. With large monolithic systems, even a minor changes to the application requires a hefty deploy process. FaaS eliminates this deploy complexity.

Using serverless code like FaaS, web developers can focus on writing application code, while the serverless provider takes care of server allocation and backend services.

<b><span style="color:green">Popular FAAS providers</span></b><br>

1. <a href="https://cloud.ibm.com/functions/">IBM Cloud Functions</a>
2. <a href="https://aws.amazon.com/lambda/">Amazon AWS Lambda</a>
3. <a href="https://cloud.google.com/functions">Google Cloud Function</a> 
4. <a href="https://docs.microsoft.com/en-us/azure/azure-functions/">Microsoft Azure function</a> 
5. <a href="https://www.openfaas.com/">OpenFaaS (OpenSource)</a>

<b><span style="color:green">Advantages of FAAS</span></b><br>
Taken in consideration there are many points which makes this model best for the cloud computing. Those are listed below.

1. Improved developer velocity
2. Builtin scalablity
3. Cost efficiency


As listed, MBAAS is better in all the terms compared to all other traditional models and all comparative models like PAAS and IAAS.


<b><span style="color:green">Disadvantages of FAAS</span></b><br>

1. Less System Control
2. More difficult to test the system




You could find more information on all of these topics from the <a href="https://dhruvdoshi.github.io/blog">home</a> page.


---

#### REFERENCES

What is Function-as-a-Service (FaaS)? (2021). Retrieved December 23, 2021, from Cloudflare website: https://www.cloudflare.com/en-gb/learning/serverless/glossary/function-as-a-service-faas/

‌What is FaaS? (2021). Retrieved December 23, 2021, from Redhat.com website: https://www.redhat.com/en/topics/cloud-native-apps/what-is-faas

‌Wikipedia Contributors. (2021, December 9). Function as a service. Retrieved December 23, 2021, from Wikipedia website: https://en.wikipedia.org/wiki/Function_as_a_service

‌