---
layout: page
title: "Reboot"
description: "Reboot"
release_date: 2016-11-13 15:00:00 -0500
sidebar: true
comments: false
sharing: true
footer: true
redirect_from: /ecosystem/hadashboard/reboot/
---

To run Dashing and `hapush` at reboot, checkout out the sample init scripts in the `./init` directory. These have been tested on a Raspberry Pi - your mileage may vary on other systems.

Instructions for automatically starting a Docker installation can be found [here](https://docs.docker.com/engine/admin/host_integration/).

For Docker you may also want to use `docker-compose` - there is a sample compose file in the `./init` directory.
