---
layout: default
title: The F# Core Engineering Group Goals, Remit and Activities
---

# The F# Core Engineering Group: Goals and Remit
{:.no_toc}  

This document describes the goals, remit and activities of the F# Core Engineering Group.

## Contents  
{:.no_toc}  

{:toc}  

## Goals

To organise, promote and contribute to work on F#'s core tooling to make development pain free and fully featured, enable it on new platforms, host F# code in new ways and ensure best-practice engineering in the F# community.

## Group Remit

The group's remit covers the following areas:

### Language Design Process

We run the [F# Language and Core Library Design Process](http://fsharp.github.io/2016/09/26/fsharp-rfc-process.html).  This
includes [F# Language Design UserVoice](http://fslang.uservoice.com).

### Compiler, Core Library and Compiler Service 

The group commits to ensuring the easy availability of the F# Compiler, Core library and Compiler Service on all major platforms at high quality. Particular points of activity are:

- We work cooperatively with the Visual F# compiler team at Microsoft to allow open source contributions and integrate Microsoft updates to the F# open source release into the F# repositories on GitHub.  
  (See [this blog entry](http://fsharp.github.io/2014/06/18/fsharp-contributions.html) and [the Visual F# Team priorities](https://visualfsharp.codeplex.com/wikipage?title=Current%20Priorities%20))

- We work cooperatively with Xamarin to integrate the F# Compiler into Mono releases on the Mac and Linux

- We enable testing for the open edition of the F# compiler, particularly through CI systems (Travis and AppVeyor)

- We work cooperatively with  Debian packaging and other distributions to ensure Linux packages are available for F# on Debian and RPM, Gentoo/Arch builds

- We work cooperatively with the Visual F# compiler team to align code bases with Visual F# team repos

- We aim to keep the  [the homebrew formula](https://github.com/Homebrew/homebrew-core/blob/7a4dabfc1a2acd9f01a1670fde4f0094c4fb6ffa/Formula/mono.rb) for F# up-to-date

- We help maintain and improve the PCL (Portable Class Library) and .NET Standard support for F# across multiple platforms and devices

- We aim to improve the documentation quality of the core compiler and library components.

- We aim to help facilitate cross-platform development on the compiler, core library and compiler service.


### Editing/IDE Tools

The group aims to help the F# community deliver high quality, consistent, easy-to-install, reliable editing experiences for F# code on all major platforms and as many editors as feasible. We also aim to encourage and facilitate Notebook/Workbook experiences (e.g. iPython notebook)


### Package Management

The group aim to contribute to improving package management and tools that support cross-platform F# development.


### Virtual Machine Images/Containers

The group encourages and facilitates the creation of pre-bundled VM images and containers which include F#, e.g.

- Docker (e.g. [The Official Docker F# Image](https://github.com/fsprojects/docker-fsharp)

- Vagrant (e.g. [this image](https://github.com/intellifactory/vagrant-fsharp/blob/master/ubuntu-trusty/Vagrantfile)

### Continuous Integration

The group aim to 

- Improve CI support for F# in common CI systems such as Travis, AppVeyor

- Share knowledge and best practice for CI systems, encourage use of CI

- Use CI for core F# community projects 


## Libraries and Frameworks

The group aims to 

- Facilitate an active, high-quality ecosystem of F# libraries. 

- Maintain and improve [the F# Component Design Guidelines](http://fsharp.org/specs/component-design-guidelines/)

We especially focus on libraries using the FSharp.* namespace. This includes

- Contributing to libraries and frameworks

- Assessing the quality of libraries and frameworks

- Reviewing library and framework designs

- Working with projects like FSharpx and ExtCore to create a cohesive set of libraries and packages

- Starting new library projects

- Proactively deprecating existing libraries

We focus on tooling to support the generation of libraries by the F# community

- Documentation tooling

- NuGet cross-platform

- PCL (portable class libraries) on all platforms

We will consider having the FSSF “blessed” libraries and tools through one or more of:

- Publishing them under a FSSF NuGet accounts

- Documenting them under fsharp.org 

- Blessing them as “supported”, where they are considered a very official and stable part of the F# library base

The criteria for a library or framework to get this blessing will be rigorous -  for example it must be uniquely significant F# functionality, not be experimental and must be stable and tested. It should also be cross-platform, where possible. 

We will look for inspiration from other package-based software communities for how to manage this process.

We will loko to improve existing Type Providers and ensure they work cross platform.


### Hosting

The group aims to facilitate the development of new F# development experiences through “hosting” F# (whether client-side as an API, server-side or other variations).


### Documentation

The group commits to 

- maintaining and regularly validating the “getting started” guides already available on fsharp.org 

- creating and maintaining development guides for all major platforms on fsharp.org 

- Make tools that generate top-quality documentation (e.g. FSharp.Formatting) and help disseminate these to the F# community.

- Better documentation for all of the impressive work that has already been done

- Help the community create roadmaps for core libraries to improve functionality, engineering, and documentation


### Interoperability

The group aims to facilitate and encourage core interoperability tooling such as

- Type providers to other programming languages (Java etc.)

- Knowledge of tooling that can be used to interoperate with other systems

### Distributed Computing Frameworks

While not part of the core remit of the group, we keep an eye on and encourage/facilitate the emerging distributed compute frameworks which work well with F# code, for example,  Akka.NET,  M-Brace/Cloud-F# and Orleans.


## What We Don’t Do

We don’t maintain every library and tool that the F# community creates. Only the following components are “maintained” by this group. 

- [The open edition of the F# compiler and core library](http://github.com/fsharp/fsharp)

- [The F# Compiler Service](http://github.com/fsharp/FSharp.Compiler.Service)

- [The F# RFC Process](http://github.com/fsharp/fsharp.github.io) and [FSharpLangDesign Notes](http://github.com/fsharp/FSharpLangDesign)

All other projects are done on a cooperative basis with the project owners and F# community.

We don’t duplicate functionality available in the F# exosystem (.NET, C#, NuGet etc.)

We don’t focus on tools/libraries clearly in the remit of another working group, e.g. math libraries. We will, however, work with these groups to help make sure their libraries and tools fit into a cohesive and simple overall picture for F#.

We don’t allow junk libraries and tools to “hang around” if they are dead projects or low quality.

We don’t focus on tooling that relies on other minority 3rd party proprietary editors. (Xamarin is OK because it also works in MonoDevelop, Resharper is not, partly because the API is complex. Visual Studio tooling is OK because it is so massive in the F# ecosystem)

Larger projects such as improved mobile support will probably need to end up as separate discussions with teams of volunteers. Most of these are mentioned in ‘Initial Remit’ above.

<br />
 
_Published: 02 July 2013_  
_Updated: 19 September 2014_  
_Updated: 27 September 2016_

_(on behalf of the F# Core Engineering group)_
