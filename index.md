---

layout: col-sidebar
title: OWASP APICheck
tags: apicheck
type: tool
level: 2
pitch: The DevSecOps toolset for HTTP APIs

---
![APICheck](/assets/images/apicheck-logo.png)

## APICheck - The DevSecOps toolset for HTTP APIs

APICheck **is an environment** for integrating existing HTTP APIs tools and create
execution chains easily. Designed with **integration third party tools in mind**.

APICheck is comprised of a set of tools that can be connected to each other to achieve
different functionalities, depending on how they are connected. It allows you to
**create execution chains**

### Why another REST APIs tool?

APICheck aims to be a universal toolset for testing REST APIs, allowing you to mix
and match the tools it provides, while enabling interoperability with third party
tools. This way we hope that it will be useful to a wide spectrum of users that need
to deal with REST APIs.

### Who is APICheck for?

APICheck focuses not only in the security testing and hacking use cases, the goal
of the project is to become a complete toolset for DevSecOps cycles. The tools are
aimed to different user profiles:

- Developers
- System Administrators
- Security Engineers & Penetration Testers

### Pipelines & data flow

In *NIX, you can chain multiple commands together in a pipeline. Consider this one:

![Unix pipeline](/assets/images/apicheck_unix_pipeline.png)

In a similar way, you can build APICheck pipelines by chaining the different tools
together.

To allow interoperability among commands and tools, all of them share a common JSON
data format. In other words, APICheck commands output JSON documents, and accept them
as input, too. This allows you to build pipelines (as we showed in the previous section).

![Data formats](/assets/images/data_format.png)

## Contribution

If your are a tool developer you can integrate with APICheck tools in no more than
**10 minutes**. Please check the [Integrating new tools guide](https://bbva.github.io/apicheck/docs/integrating-new-tools)

## Licensing

This project is distributed under [Apache 2 license](https://github.com/bbva/apicheck/raw/master/LICENSE).
