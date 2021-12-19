<!--
  ~ Licensed to the Apache Software Foundation (ASF) under one
  ~ or more contributor license agreements.  See the NOTICE file
  ~ distributed with this work for additional information
  ~ regarding copyright ownership.  The ASF licenses this file
  ~ to you under the Apache License, Version 2.0 (the
  ~ "License"); you may not use this file except in compliance
  ~ with the License.  You may obtain a copy of the License at
  ~
  ~   http://www.apache.org/licenses/LICENSE-2.0
  ~
  ~ Unless required by applicable law or agreed to in writing,
  ~ software distributed under the License is distributed on an
  ~ "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
  ~ KIND, either express or implied.  See the License for the
  ~ specific language governing permissions and limitations
  ~ under the License.
  ~
-->
# Nuvolaris

Welcome to the Nuvolaris project. 

This is an [ongoing project](#about), that is still in early stages, to build an Open Source distribution of [Apache OpenWhisk](https://openwhisk.apache.org) licensed released under the [Apache Licence 2.0](LICENSE) (like OpenWhisk itself)

There are currently no releases yet. Our first release is scheduled for January 2022.

## TL;DR

Too lazy to read?

- Chat with us on [Discord](https://discord.gg/VSGG7aQ2Ds)
- Discuss with us on [Forum](https://github.com/nuvolaris/nuvolaris/discussions/)
- Give a look our [Roadmap](docs/ROADMAP.md).
- Check the [overview](docs/OVERVIEW.md)

If you want to contribute, **YOU HAVE TO PUT YOUR CODE UNDER A LICENSE**. Quick way to to it:

1. fork the repository where you want to contribute. 

If in doubt which one, fork `nuvolaris` we move the code in the right place

2. clone the repository and open it with VSCode

```
# change here your-github-user and nuvolaris-submodule
git clone https://github.com/your-github-user/nuvolaris-submodule
cd nuvolaris-submodule
code . 
```

Now it will ask if you want to run in a container. Say yes.

3. Add your code and **LICENSE IT**. Use `license-eye`.

After editing, open the terminal and type:

```
license-eye header fix
```

4. Commit, push and send a pull request to us.

## About

We want to build a *complete* distribution of a serverless environment that is:

- it is easy to install and manage
- potentially runs in every Kubernetes, but it works on a tested set
- includes a good set of integrated services

This is the main differentiation from Apache OpenWHisk as it only provides a basic engine for serverless.  Our goals are described in our [**roadmap**](docs/ROADMAP.md) document to read about.

If you want to help here is how:

- [Get in touch](#get-in-touch)
- [What is the next activity?](#what-is-the-next-activity)
- [How to contribute](#how-to-contribute)

## Get in touch

Do you want to help?

- Start [introducing yourself in the forum](https://github.com/nuvolaris/nuvolaris/discussions/7) and partecipating to discussions.
- Chat with us joining our [discord server](https://discord.gg/VSGG7aQ2Ds).   Note there is a channel for every repository in the project to discuss specific issues.

## What is the next activity?

We split activities in milestones. We give to them a friendly name and we name milestones after characters the movies of The Matrix franchise. 

The  current milestone (the first one) is [Neo](docs/Neo.md). And of course the milestone to reach to release 1.0 is [Matrix](docs/Matrix.md).
 
Future Milestones will be named Trinity, Morpheus, Agent Smith and so on.

To manage the milestones we use [GitHub Projects](https://github.com/nuvolaris/nuvolaris/projects) that in turn uses  the [GitHub Issue Tracker](https://github.com/nuvolaris/nuvolaris/issues).

## How to contribute

In order to contribute to our project:

- Review the [Code Contribution](docs/CONTRIBUTING.md) rules. In particular we need you sign the [Apache CLA (Contributor License)](http://www.apache.org/licenses/#clas) and include the  [Apache License Header](https://www.apache.org/legal/src-headers.html) in every file. Also every PR will have to pass the existing tests (there are none yet but there will be).
- Either find an open and unassigned issue, or open one by yourself in the [Issue Tracker](https://github.com/nuvolaris/nuvolaris/issues) describing what you want to do.
- Please discuss *in the forum*  and ensure you want to do is approved by the [project owners](OWNERS.md), if you want to be sure your PR will be merged. We can still merge unsolicited PR, but if you do not discuss it before there is some risk that for some reason we may unable to merge it. -
- Get an issue assigned. Seriously. 
- Code it!
- Submit a Pull Request and get it merged after the review.


