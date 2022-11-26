<!--
SPDX-FileCopyrightText: 2022 Sidings Media <contact@sidingsmedia.com>
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Railway Controller

The railway controller is a project run by [Sidings
Media](https://github.com/SidingsMedia). It is a complete system to control your
model railway by computer without having to modify your existing rolling stock
in any way shape or form.

## Contributing

We love it when people contribute to our projects, it is what makes open source
so great. To help you with contributing, here are a couple of tips.

* When creating an issue, please provide as much detail as possible. It will
  really help us to track down the issue
* When creating a pull request, add descriptions and make sure your commits have
  meaningful commit messages
* Don't be affraid to ask for help if you get stuck. We are more than happy to
  give you a hand with your contribution if you need it. It is how we all learn
  and get better

<!-- TODO: Add contributing section to the docs -->
<!-- TODO: Add docs -->
<!-- For more details on how to contribute, please take a look at the contributing
section of the docs. -->

## Repositories

This project is split up into a number of repositories within this organisation.
Each repository contains a single self contained component of the system ranging
from boards to bootloaders and client software. Each board repo, e.g. the
[maincontroller](https://github.com/RailwayController/maincontroller) repository
contains the board designs and schematics. A second repo is used to store the
firmware for this board. The repo's name is the name of the designs repo with
`-fw` appended to the end. Using the `maincontroller` example, the firmware repo
would be `maincontroller-fw`. This is done to ease versioning of both hardware
and firmware.

<!--
TODO:

👩‍💻 Useful resources - where can the community find your docs? Is there 
anything else the community should know?
-->
