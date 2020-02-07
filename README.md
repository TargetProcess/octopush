# Octopush
A set of services that facilitates Continuous Delivery to K8s clusters in a GitOps way.

## What is that all about?
Octopush facilitates **Continuous Delivery** of **Helm** releases to **K8s** clusters.
Written in **Typescript** as a set of **microservices** (with a **Monorepo** approach via **lerna** under the hood).

From day 0 **Octopush** was designed with focus on:
* scalability for dozens of clusters
* end users with different background (not only DevOps teams)
* a purely declarative GitOps approach (with the whole state stored in **Git** as a single source of truth)
* escalated security requirements
* transparency and observability for each and every deployment
* automation

## What is the current state?
Octopush is being developed and used internally at Targetprocess for several years already,
allowing us to successfully manage our 30+ (and growing) production clusters with dozens and hundreds of microservices hosted on each.

We're currently considering options to make the tool open-source.
The main goals for that are:
* sharing the tool, so that the community could make use of it
* gathering people who are enthusiastic about GitOps approach and the tool itself to improve it
* starting the intake of ideas from the community

Still some technical debt fighting and dependencies minimalization must be done as a prerequisite for publishing **Octopush** sources to the world.

**We're gonna do our best to do all neccessary preparations ASAP and add the sources here for everyone to consume and contribute to.**

## Great, how can I help you?
If you have thoughts/ideas/feedback or would like to participate as a developing member, please, **feel free to contact us** (via Github issues here, or by dropping a mail to devops(a)targetprocess.com, or by any other way you like).

You may also ⭐star this project and/or start 👀 watching it in order to show your interest and motivate us, so we'll know we're on the right way and accelerate our efforts.
