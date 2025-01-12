# Onboarding and Deploying Components
* [Introduction](#introduction)
* [Goals](#goals)
* [Prerequisites](#prerequisites)
* [An Example Component](#an-example-component)
* [Deploying the Component](#deploying-the-component)


## Introduction
In this guide we show how to onboard and deploy a third party component using the Cisco MSX Portal.


## Goals
* onboard and deploy a third party component into MSX


## Prerequisites
* access to an MSX environment [(help me)](../01-msx-developer-program-basics/02-getting-access-to-an-msx-environment.md)
* an MSX Component tarball [(help me)](artifacts/helloworldservice-1.0.0-component.tar.gz)


## An Example Component
First you must make or download an MSX Component before you can deploy it. They are distributed as tarballs containing a manifest and container(s), for convenience you can download one [here](artifacts/helloworldservice-1.0.0-component.tar.gz).


## Deploying the Component
Open Cisco MSX Portal and log in as superuser then navigate to "Settings->Component Manager".

![](images/deploying-component-1.png?raw=true)

<br>
Select "Add Component" and pick the file "helloworldservice-1.0.0-component.tar.gz" then click "Upload" and follow the instructions.

![](images/deploying-component-2.png?raw=true)

<br>
Once the upload has finished a message box will indicating success of failure.

![](images/deploying-component-3.png?raw=true)

<br>
After the message box has been dismissed the new component will appear in the list.

![](images/deploying-component-4.png?raw=true)


| [PREVIOUS](03-service-containerization-and-packaging.md) | [NEXT](05-service-offers-and-subscriptions.md) |  [HOME](../index.md#msx-component-manager) |
