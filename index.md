---
layout: default
---


# What is UpStreamI?

Updating a project dependencies is often a scary and time consuming task, many of us dread the day we need to run `pip install --upgrade` or `flutter upgrade` as often it leads to all sorts of errors requiring time consuming investigations.

With UpStreamI your project is constantly tested against the development branch of your dependencies, if a dependency change is breaking your project UpStreamI notifies you, pinpointing the exact commit that is breaking your project (where often you'll find a useful description of what needs to be changed in your project). UpStreamI helps package maintainers avoid unintended breaking changes and estimate the impact of a breaking change by notifying them when a change broke a number of dependent projects.

UpStreamI is [shifting left](https://en.wikipedia.org/wiki/Shift-left_testing) cross-package testing, and reducing engineering overhead across the ecosystem.

# Supported languages

We currently support building projects that use one or more of the following languages:
  - C/C++
  - Dart
  - Golang
  - Java
  - Python

We're working on adding more toolchains!

# Does UpStreamI needs access to my code?

The easiest way to use UpStreamI is to grant it access to your private repository.
If you want to install an UpStreamI service on your VPC please reach out to: <beta@upstreami.com>.

# Is it free?

We're charging for the incremental compute resources needed to add your project to our global build graph,
note that as we're caching intermediate build artifacts across projects you share the cost with other projects with common dependencies.

The typical monthly cost for a medium-large sized project with about ~400 transitive dependencies is around 80 USD.

# How do I use it?

We're currently running a closed beta, we are looking to add some more participants!
If you want to try it out please let us know at <beta@upstreami.com>.

# Get in touch
Feel free to reach out at <beta@upstreami.com>
