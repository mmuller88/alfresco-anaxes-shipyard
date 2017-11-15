# Welcome to Anaxes Shipyard

The purpose of the Anaxes Shipyard project is to provide a set of guidelines, best practices and artifacts Alfresco engineering teams can use to produce deliverables ready for deployment into [Kubernetes](https://kubernetes.io).

Whilst this project is primarliy aimed at internal engineering teams the contents may also be useful to the community, partners and customers.

# What's in This Project?

This section describes the parts Anaxes Shipyard is comprised of and provides links to where you'll find more information. 

## Guidelines

To ensure we have a consistent approach to building, deploying and running deliverables from each delivery team we need to have a set of [guidelines](./docs/guidelines/README.md) we all adhere to.

## Docker Images

Components of the Alfresco platform should produce [Docker](https://www.docker.com) images as part of their build and release pipeline. In order to eliminate duplication and provide consistency the Anaxes Shipyard project will define several base Docker images that components can use as the starting point for their images.

The Alfresco [base Java docker image](https://github.com/Alfresco/alfresco-docker-base-java) defines the starting point for any product/service that requires Java.

## Helm Charts

[Helm](https://github.com/kubernetes/helm) is a packaging technology that will be used to deploy Alfresco products to Kubernetes.

Similar to producing Docker images, components should also produce helm charts to package their deliverables. The Anaxes Shipyard project also provides some examples.

## Architectural Decision Records (ADRs)

Every architectural decision made as part of this project is being documented as an ADR, you can find them [here](./docs/adrs).

# Getting Started

## How to Run a Kubernetes Cluster

To help new starters to get a Kubernetes Cluster up and running quickly we documented the steps required to run it locally or on AWS [here](./docs/running-a-cluster.md).

## Check Out the Hello World App Example

To practically demonstrate the use of the guidelines and artifacts generated by Anaxes Shipyard a [Hello World App](https://github.com/Alfresco/alfresco-anaxes-hello-world) has been produced.

## Tips and Tricks

During development of the project we had some findings about how to do things easier. We documented them [here](./docs/tips-and-tricks.md).

# Contributing to Anaxes Shipyard

We encourage and welcome contributions to this project. For further details please check the [contributing](./CONTRIBUTING.md) file.
