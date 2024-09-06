# Data on Kubernetes - Getting Started Guide

Contributors: Paul Au,

## Project Description

The barrier to entry for any technology and community surrounding that technology can often be quite high. The purpose of this document is to capture existing resources that we can leverage to help create a roadmap for DoK beginners.

The secondary purpose of this document is to capture gaps in existing content so we can, as a community, create content to fill those gaps.

## Goals

Provide a set of resources to help guide a complete beginner with the base set of knowledge to start running data workloads on Kubernetes.

We will break the content into sections in a logical order to guide someone from DoK beginner to deploying their first stateful application on kubernetes.

## Table of Contents
- [Why Stateful on Kubernetes?](#why-stateful-on-kubernetes)
- [Intro to Stateful](#intro-to-stateful)
  - [Purpose](#purpose)
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
  
## Why Stateful on Kubernetes

According to past DoK reports, the following are some of the reasons 
- Kubernetes has become a core part of IT – half of the respondents are running 50% or more of their production workloads • on it, and they are very satisfied and more productive as a result. The most advanced users report 2x or greater productivity gains.
-Business demands are creating pressures for further adoption. The increasing importance of real-time data to competitive advantage will sharpen companiesʼ need to run data on Kubernetes. A majority believe standards will improve data management and that data should become declarative.
-Standardization is the key driver for Kubernetes Leaders


## Intro to Stateful

### Purpose

Provide basic knowledge of what stateful means in Kubernetes.

### Resources

- [Documentation on Stateful Sets from Kubernetes](https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/)
- [Stateful Workloads in Kubernetes: A Deep Dive - Kaslin Fields & Michelle Au, Google](https://youtu.be/688K9UlEbPk?si=BNH7a5JWMlZWtbyU)

## Types of workloads

### Purpose

Provide a list of stateful workloads that exist on Kubernetes and a description/examples of each workload
Stateful Workloads

- Databases (stateful sets or CRD)
- AI/ML (usually jobs) - [https://developers.redhat.com/aiml/ai-workloads](https://developers.redhat.com/aiml/ai-workloads)
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


## Operators 101

### Purpose

Provide resources explaining what operators are and what role they play in running data workloads on kubernetes.

### Resources:

- [What is a kubernetes Operator](https://www.redhat.com/en/topics/containers/what-is-a-kubernetes-operator)
- [What are Kubernetes Operators (Operators 101 :part 1)](https://sklar.rocks/what-are-kubernetes-operators/)
- [Operator Pattern](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
- [Custom Resource Definitions](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)
- [An Introduction to Custom Resource Definitions and Custom Resources (Operators 101: Part 2)](https://sklar.rocks/kubernetes-custom-resource-definitions/)
- [Operator Hub]( https://operatorhub.io/) OR visit
https://www.cncf.io/blog/2022/06/15/kubernetes-operators-what-are-they-some-examples/

### Common Operators
- [CloudNativePG](https://cloudnative-pg.io/) 

## Common Tools

### Purpose

Provide resources explaining what operators are and what role they play in running data workloads on kubernetes.

### Resources:

- MiniKube: Used for running kubernetes locally

## Ecosystem 101

### Purpose

List and describe open source projects that are a part of the DoK Ecosystem. This list is not comprehensive.

- [DoK Landscape](https://dok.community/landscape/)

### Databases
- [Vitess](https://vitess.io/) - MySQL-compatible, horizontally scalable, cloud-native database solution
- [Cassandra](https://cassandra.apache.org/_/index.html) - Apache Cassandra is a highly-scalable partitioned row store. Rows are organized into tables with a required primary key.
- [PostgreSQL](https://www.postgresql.org/) - PostgreSQL is a powerful, open source object-relational database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads.

### Cloud Native Storage

- Rook - Rook is an open source cloud-native storage orchestrator, providing the platform, framework, and support for Ceph storage to natively integrate with cloud-native environments.
- CubeFS - CubeFS is a new generation cloud-native open source storage system that supports access protocols such as S3, HDFS, and POSIX.
- Longhorn - Longhorn is a lightweight, reliable and easy-to-use distributed block storage system for Kubernetes.


### Streaming
- Kafka
- Spark
- Flink
- Kubeflow
- Strimzi

## Deploy your first database on kubernetes

### Purpose

In this section, you'll learn how to use the knowledge you've accumulated to deploy a database to kubernetes.

### Resources:

## Next Steps

### Purpose
In this section, we'll list some resources to push you to the next level of understanding.

### Resources:
