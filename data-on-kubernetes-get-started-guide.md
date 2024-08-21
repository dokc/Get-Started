# Data on Kubernetes - Getting Started Guide

Contributors: Paul Au, 

## Project Description
The barrier to entry for any technology and community surrounding that technology can often be quite high. The purpose of this document is to capture existing resources that we can leverage to help create a roadmap for DoK beginners. 

The secondary purpose of this document is to capture gaps in existing content so we can, as a community, create content to fill those gaps.

## Goals
Provide a set of resources to help guide a complete beginner with the base set of knowledge to start running data workloads on Kubernetes.

We will break the content into sections in a logical order to guide someone from DoK beginner to deploying their first stateful application on kubernetes.

## Table of Contents

- [Data on Kubernetes - Getting Started Guide](#data-on-kubernetes---getting-started-guide)
  - [Project Description](#project-description)
  - [Goals](#goals)
  - [Table of Contents](#table-of-contents)
    - [Intro to Stateful](#intro-to-stateful)
      - [Purpose:](#purpose)
      - [Resources](#resources)
    - [Types of workloads](#types-of-workloads)
      - [Purpose](#purpose-1)
    - [Operators 101](#operators-101)
      - [Purpose](#purpose-2)
      - [Resources:](#resources-1)
    - [Common Tools](#common-tools)
      - [Purpose](#purpose-3)
      - [Resources:](#resources-2)
    - [Ecosystem 101](#ecosystem-101)
      - [Purpose](#purpose-4)
      - [Resources:](#resources-3)
    - [Deploy your first database on kubernetes](#deploy-your-first-database-on-kubernetes)
      - [Purpose](#purpose-5)
      - [Resources:](#resources-4)
    - [Next Steps](#next-steps)
      - [Purpose](#purpose-6)
      - [Resources:](#resources-5)

### Intro to Stateful 
#### Purpose: 
Provide basic knowledge of what stateful means in Kubernetes
#### Resources
- <a href="https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/" target="_blank">Documentation on Stateful Sets from Kubernetes</a>
- [Stateful Workloads in Kubernetes: A Deep Dive - Kaslin Fields & Michelle Au, Google](https://youtu.be/688K9UlEbPk?si=BNH7a5JWMlZWtbyU){:target="_blank"} 

### Types of workloads

#### Purpose
Provide a list of stateful workloads that exist on Kubernetes and a description/examples of each workload
Stateful Workloads

- Databases (stateful sets or CRD)
- AI/ML (usually jobs)
- Batch processing jobs
- Stream processing
- Machine learning and AI workloads
- Data analytics
- ETL (Extract, Transform, Load) pipelines
- Data warehousing						
- Distributed databases
- In-memory data grids
- Time series databases
- Search and indexing engines


### Operators 101
#### Purpose
Provide resources explaining what operators are and what role they play in running data workloads on kubernetes

#### Resources:
- What is a kubernetes Operator: https://www.redhat.com/en/topics/containers/what-is-a-kubernetes-operator
- What are Kubernetes Operators (Operators 101 :part 1) : https://sklar.rocks/what-are-kubernetes-operators/
- Operator Pattern: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- Custom Resource Definitions : https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/
- An Introduction to Custom Resource Definitions and Custom Resources (Operators 101: Part 2) : https://sklar.rocks/kubernetes-custom-resource-definitions/
- Operator Hub: https://operatorhub.io/
https://www.cncf.io/blog/2022/06/15/kubernetes-operators-what-are-they-some-examples/


### Common Tools
#### Purpose
Provide resources explaining what operators are and what role they play in running data workloads on kubernetes.

#### Resources:
- MiniKube: Used for running kubernetes locally

### Ecosystem 101
#### Purpose
Describe all of the open source projects that are a part of the DoK Ecosystem

#### Resources:
- DoK Landscape: https://dok.community/landscape/
= Kafka
- Spark
- Kubeflow

### Deploy your first database on kubernetes
#### Purpose
In this section, you'll learn how to use the knowledge you've accumulated to deploy a database to kubernetes

#### Resources:

### Next Steps
#### Purpose
In this section, we'll list some resources to push you to the next level of understanding.

#### Resources:
