# devopsinfourweeks



There has never been a better time to launch your DevOps career, and this 4-week course provides the training and knowledge you need to get started. This series explores the concepts you need to learn, but more than that, helps you build your own skills through homework assignments and doing the actual work needed to truly gain proficiency.

Week 1 introduces you to core DevOps technologies and details how DevOps has influenced the way applications are offered. You learn about configuration as code, working with Git, CI/CD, containers, microservices, and other core DevOps technologies so you can best understand why all of these work so well together.

Week 2 focuses on jumpstarting your containers knowledge and skills. You explore microservices and then jump into both the Docker approach and Podman. You also learn how to package your application in an image, which you can then run as a container.

Week 3 is all about Kubernetes. There’s a lot to explore on this topic, and we start with detailing how to bring containers to the data center. Running stand-alone containers is nice, but running containers as a cluster is more efficient and scalable and allows you to build your microservices solution so you can avoid headaches down the road.

In Week 4 you learn about OpenShift, the platform that brings it all together. In OpenShift you integrate your Git-based CI/CD pipelines and work with YAML to manifest files to automate the build process from source code to an application, running as a container in your data center.
What you'll learn-and how you can apply it

At the end of this live, hands-on, online course you'll be able to:

    Run your source code as an application in a container
    Connect multiple containers together in a microservice
    Scale and orchestrate container workloads in Kubernetes
    Automatically build applications from source code and run them in OpenShift

This training course is for you because...

    You are a developer who wants to learn all about running applications as containers
    You are a systems administrator who wants to know how to do sysadmin work in the era of containers
    You're looking for an easy way to automate the application build process

Prerequisites

    Basic knowledge about Linux is recommended.

Course Set-up

    For weeks 1 and 2 of this course, students are recommended to use two virtual machines. One virtual machine that has a standard installation of Ubuntu LTS 20.04 workstation, and another virtual machine that has a minimal installation of CentOS 8.x. Additional setup instructions can be found in the course github repository https://github.com/sandervanvugt/devopsinfourweeks
    For week 3 of this course, access to a Kubernetes cluster is required. Setup of Kubernetes is explained in week 2 of the course. To run a Kubernetes cluster based on Minikube, students will need to use Ubuntu LTS 20.04 workstation with at least 4GB of RAM
    For week 4 of this course, running a virtual machine with OpenShift is required. The OpenShift virtual machine needs a minimum of 9 GB of RAM. Setup instructions will be provided in week

Recommended Preparation

    You should have an understanding of Linux basics before taking this course. Please take a look at my video course Linux Fundamentals if you need to hone your skills before the class.

Recommended Follow-up

    Kubernetes: From Basics to Guru: https://learning.oreilly.com/playlists/330a1112-13ee-4e72-8b2a-6fd8766fddae/
    OpenShift Fundamentals: https://learning.oreilly.com/videos/red-hat-openshift/9780135767436

About your instructor

    Sander van Vugt started working with Linux in 1992. He wrote his first book about Linux in 1999, and up to date has completed 62 different books on Linux related topics, including the best selling titles like the RHCSA Complete Video Course and the Certified Kubernetes Application Developer (CKAD) Crash Course as well as many other open source platform titles. He also works as a Linux instructor, teaching on-site and on-line classes for customers around the world.




Schedule

The timeframes are only estimates and may vary according to how the class is progressing
Week 1: Introduction to DevOps Technologies

Introduction (18 minutes)

    4 day class expectations and agenda

Understanding DevOps (30 minutes)

    Understanding the DevOps way of working
    Exploring DevOps core ingredients

BREAK

Using Git (48 minutes)

    Understanding Git
    Managing Git Repositories

BREAK

Using CI/CD (20 minutes)

    Understanding CI/CD
    Working with CI/CD pipelines

Understanding Microservices (28 minutes)

    Microservices Introduction
    From Monolithc applications to Microservices
    Understanding Microservices Key protocols

BREAK

Using Containers in Microservices (38 minutes)

    Understanding the role of Containers in Microservices
    Setting up an environment to work with containers

Week 1 homework assignment and Q&A (10 minutes)
Week 2: Managing Containers

Discussing Week 1 Homework Assignment (10 minutes)

Understanding Containers (30 minutes)

    Understanding Containers
    Selecting a platform to run containers
    Understanding Container standardization

Running Containers in Docker or Podman - Part 1 (18 minutes)

    Using Images from Registries

BREAK

Running Containers in Docker or Podman - Part 2 (48 minutes)

    Managing Running Containers
    Understanding Podman Rootless Containers

BREAK

Managing Container Images (40 minutes)

    Finding Container Images
    Building Container Images with Dockerfile
    Exporting and Importing Container Images
    Optimizing Container Image Builds

Managing Container Storage (20 minutes)

    Understanding Container Storage
    Managing Persistent Storage

BREAK

Accessing Container Workloads (25 minutes)

    Understanding Container Networking
    Providing Access to Containerized Applications

Exploring Week 3 Setup and Homework (25 minutes)

    Accessing Kubernetes in Google Cloud
    Running Kubernetes in Minikube
    Week 2 Homework Assignment

Week 3: Managing Kubernetes

Week 2 Homework discussion (10 minutes)

Understanding Kubernetes (20 minutes)

    Kubernetes use and origins
    Understanding Kubernetes Resource Types

Running Applications in Kubernetes - Part 1 (18 minutes)

    Working with kubectl

BREAK

Running Applications in Kubernetes - Part 2 (48 minutes)

    Using a declarative versus imperative approach
    Understanding YAML files
    Understanding the API
    Managing Application Scalability

BREAK

Exposing Applications (24 minutes)

    Working with Services
    Working with Ingress

Configuring Application Storage (24 minutes)

    Understanding Pod Volumes
    Providing Access to Persistent Storage

BREAK

Implementing Decoupling in Kubernetes (45 minutes)

    Using PVC in decoupled workloads
    Using ConfigMaps and Secrets

Exploring Week 4 setup and homework (15 minutes)

    Preparing the week 4 OpenShift setup
    Week 3 homework

Week 4: OpenShift

Discussing Week 3 Homework Assignment (10 minutes)

Exploring what OpenShift adds to Kubernetes (38 minutes)

    Understanding OpenShift
    OpenShift unique features
    Exploring OpenShift Console

BREAK

Running Kubernetes Applications in OpenShift (48 minutes)

    Using oc new-app
    Exposing OpenShift applications

BREAK

Building OpenShift Applications from Git Source Code (48 minutes)

    Understanding S2I
    Running Applications with S2I

BREAK

Configuring OpenShift Authentication and Authorization (38 minutes)

    Configuring OpenShift User Accounts
    Setting up OpenShift RBAC

What's next and Q&A (10 minutes)
