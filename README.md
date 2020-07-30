# The OpenDTO Specification

![Circle of Enlightenment](https://i.ibb.co/GJkbxgm/1-JLPpr0r85-X0a7yto-NVgfhw-9806703.jpg)

## Our Goal

The OpenDTO Specification is currently a question, "Can we represent any data model universally?. Similiar to the research that Google Labs released on Protocol Buffers; OpenDTO's main object is to see if we can create a compiler that can generate data models which can interchangeably work with any programming language agnostically. Accomplishing this solution will allow our ever growing IoT and embedded control processors (arduino, 3d printers, robotics, etc.) to communicate together through machine code. This is a requirement when streaming data between classical and quantum computer systems. Without a universal algorthm to build and validate these buffer's... well lets get coding!

## The Specification

The OpenDTO Specification (ODS) defines a standard, programming language-agnostic interface description for HTTP DTOs (Data Transfer Objects), which allows both humans and computers to discover and understand the capabilities of data modeling without requiring access to source code, database  sql, additional documentation, or inspection of network traffic. When properly defined via OpenDTO, a consumer can understand and interact with nonlocalized data models with a minimal amount of implementation logic. Similar to what interface descriptionshave done for lower-level programming, the OpenDTO Specification removes guesswork in sharing and using data models.

Use cases for machine-readable DTO definition documents include, but are not limited to: interactive documentation; code generation for documentation, clients, and servers; and automation of test cases. OpenAPI documents describe an APIs services and are represented in either YAML or JSON formats. These documents may either be produced and served statically or be generated dynamically from an application. This project also is trying to create a WASM compiler for a DDLMO ( /dil •moe/ ~ DDL Model Object).

The OpenDTO Specification does not require rewriting existing DTOs. It does not require binding any software to a service — the service being described may not even be owned by the creator of its description. It does, however, require the capabilities of the service be described in the structure of the OpenDTO Specification. Unlike OpenAPI, all services can be described by OpenDTO — this specification is intended represent any data strcuture as an UOM (Universal Object Model). The OpenDTO Specification does not mandate a specific development process such as design-first or code-first. It does facilitate either technique by establishing clear interactions with a HTTP API and JPA Objects.

This GitHub project is the starting point for OpenDTO. Here you will find the information you need about the OpenDTO Specification, simple examples of what it looks like, and some general information regarding the project.

## Current Version - 0.0.1

The current version of the OpenDTO specification is [OpenDTO Specification 0.0.1](versions/0.0.1.md).

## Current Release Candidate Version - 1.0.0

We invite the community to help get us to our first major milestone, version 1.0. 

## Project Specification ##

Is this even possible or worth doing? This version aims to answer that. The current proposal is to build a JIT compiler for DDLMO source code that can also compile Java or Javascript into a package or module of DDLMO, and their respective header PSI (programming structure interface) for API access of your software project. All while doing this as an easy to download and use Gradle or NPM module.

### Previous Versions

This is the first version.

## See It in Action

We are currently building our first example.

## Participation

The current process for development of the OpenDTO Specification is described in 
[Development Guidelines](DEVELOPMENT.md).
Development of the next version of the OpenDTO Specification is guided by the [Democratic Software Committee (DSC)](https://www.dreamscale.io/participate/how-to-join-democratic-software-process). This group of committers bring their data modeling expertise, incorporate feedback from the community, and expand the group of committers as appropriate. All development activity on the future specification will be performed as features and merged into this branch, that are voted on by the community. Everyone is invited to provide their input and cast their vote on the direction in which we will represent and share our data models. Upon release of the future specification, this branch will be merged to master, once all have come to a consensous.

The DSC holds weekly web conferences to review open pull requests for quality, risk, and ethical review. Open discussions will be created to understand together our open issues related to the evolving OpenDTO Specification. Participation in weekly calls and scheduled working sessions is open to the community. You can view the [DSC calendar online](https://opendto.dreamscale.io/calendar), and import it to your calendar at your leisure.

The OpenDTO Initiative encourages participation from individuals and companies alike. If you want to participate in the evolution of the OpenDTO Specification, consider taking the following actions:

* Review the [current specification](versions/1.0.0.md). The human-readable markdown file _is the source of truth_ for the specification.
* Review the [development](DEVELOPMENT.md) process so you understand how the spec is evolving.
* Check the [issues](https://github.com/dreamscale-io/OpenDTO-Specification/issues) and [pull requests](https://github.com/dreamscale-io/OpenDTO-Specification/pulls) to see if someone has already documented your idea or feedback on the specification. You can follow an existing conversation by subscribing to the existing issue or PR.
* Create an issue to describe a new concern. If possible, propose a solution.

Not all feedback can be accommodated and there may be solid arguments for or against a change being appropriate for the specification.

## Licensing

See: [License (Apache-2.0)](https://github.com/dreamscale-io/OpenDTO-Specification/blob/master/LICENSE)
