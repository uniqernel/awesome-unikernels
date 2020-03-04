# Awesome Unikernels [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Secure, lightweight and high performance approach to application delivery


## Contents

- [Introduction](#introduction)
- [Projects](#projects)
  - [Linux Binary Compatible](#linux-binary-compatible)
  - [Language oriented](#language-oriented)
  - [Generic](#generic)
  - [Unikernel-like](#unikernel-like)
- [Tools](#tools)


## Introduction

- [Unikernel and Immutable Infrastructures](https://github.com/cetic/unikernels) - Introductory white paper maintained by CETIC engineers.


## Projects

### Linux Binary Compatible
- [OSv](http://osv.io) - Modular unikernel able to execute unmodified Linux binaries, developed in C++.
- [Nanos](https://github.com/nanovms/nanos) - Linux binary compatible unikernel focused on security.
- [HermiTux](https://github.com/ssrg-vt/hermitux) - Research project from Virginia Tech, demonstrating advanced optimizations.

### Language oriented
- [HaLVM](https://galois.com/project/halvm) - Port of Glasgow Haskell compiler producing Xen optimized unikernels.
- [LING](https://github.com/cloudozer/ling) - Erlang/Elixir unikernel development toolkit targeting Xen.
- [MirageOS](https://mirage.io) - OCaml unikernel development library.
- [runtime.js](http://runtimejs.org) - KVM oriented unikernel for running JavaScript applications via the V8 engine.
- [IncludeOS](https://github.com/includeos/IncludeOS) - Feature rich unikernel development library for C++.
- [Toro Kernel](https://torokernel.io) - Lazarus/FreePascal toolkit for unikernel development.
- [Ultibo Core](https://github.com/ultibohub/Core) - Lazarus/FreePascal unikernel targeting Raspberry Pi as the runtime environment.
- [rekernel](https://github.com/imbsky/rekernel) - Minimal setup for developing unikernels in ReasonML.
- [Union](https://github.com/pmuens/union) - POSIX compliant unikernel written in Rust.
- [binaryno](https://github.com/gmodena/binaryno) - Rust unikernel running on bare ARM CortexM hardware.

### Generic
- [ClickOS](http://cnp.neclab.eu/projects/clickos) - Efficient network function virtualization platform, optimized for Xen and developed by NEC.
- [Clive](http://lsub.org/ls/clive.html) - Research project from Rey Juan Carlos University (Madrid), developed in Go.
- [Mini-OS](https://wiki.xen.org/wiki/Mini-OS) - Reference kernel distributed with Xen.
- [Rump Kernels](http://rumpkernel.org) - Development platform reusing NetBSD components for producing efficient unikernels.
- [Firecracker](https://firecracker-microvm.github.io) - AWS's VM isolation engine, using in products such as Lambda and Fargate.
- [Unikraft](https://xenproject.org/developers/teams/unikraft) - Collection of building blocks for unikernel development.
- [BareMetal](https://github.com/ReturnInfinity/BareMetal) - Self described as an exokernel, it can be used as the starting point for unikernel development.
- [HermitCore](https://github.com/hermitcore/libhermit) - A C-based, lightweight unikernel project from Aachen University.
- [unicycle](https://github.com/libunicycle/unicycle) - Unikernel application framework developed in C.
- [EbbRT](https://github.com/SESA/EbbRT) - Boston University unikernel research project.
- [Nautilus](https://github.com/HExSA-Lab/nautilus) - Aerokernel from Sandia National Laboratories, supporting bare metal x86_64 and Xeon Phi.
- [JML](https://github.com/yesco/jml) - Proof of concept for a minimal web server unikernel implementing its own language.

### Unikernel-like
- [Drawbridge](https://www.microsoft.com/en-us/research/project/drawbridge) - Research prototype platform from Microsoft.
- [Graphene](https://github.com/oscarlab/graphene) - Library OS optimized for Intel SGX.


## Tools

- [OPS](https://ops.city) - Orchestration tool for building and deploying Nanos based images.
- [Capstan](http://osv.io/capstan) - Orchestration tool for packaging and running OSv based images.
- [UniK](https://github.com/solo-io/unik) - Unikernel compiler supporting a Firecracker, rump kernels, OSv, IncludeOS and MirageOS.
- [Solo5](https://github.com/Solo5/solo5) - Middle-ware interfacing unikernels with the host systems.
- [Albatross](https://github.com/hannesm/albatross) - MigrageOS unikernel orchestration, via Solo5.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
