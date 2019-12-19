<!--
******************************************************************************
Copyright (c) 2018 Dortmund University of Applied Sciences and Arts

All rights reserved. This program and the accompanying materials
are made available under the terms of the Eclipse Public License v2.0
which accompanies this distribution, and is available at
https://www.eclipse.org/org/documents/epl-2.0/index.php

Contributors:
    Robert Hoettger - initial readme files added
*****************************************************************************
-->

# Kuksa-Integration Repo

This Repository contains necessary tests for Eclipse Kuksa Platforms.

Module and Integration Test Suite containing 40 Tests in the Kuksa context.

Covers:
Eclipse Hono
Eclipse Hawkbit
Kuksa Appstore
Kuka Invehicle Platform Integration

Jenkins setup via Spring parameters
Tests can be modified via the TestData files in testing/src/test/resources/testData

# Getting Started with Eclipse Kuksa

## What can you do with Eclipse Kuksa?

* Build and deploy in-vehicle applications based on AGL (see more info [here](https://agl-kuksa.readthedocs.io/en/latest/))
* Add services to Kuksa-AGL (see more info [here](https://github.com/eclipse/kuksa.invehicle/tree/master/agl-kuksa)) to build custom AGL-based in-vehicle HMI systems
* Setup a cloud cluster consisting of Eclipse Hono, Eclipse HawkBit, the Kuksa Appstore, and more to provide a connected vehicle ecosystem (see more info [here](https://github.com/eclipse/kuksa.cloud))
* Setup an Eclipse Che based APPSTACLE IDE to either develop, build, and deploy cloud or in-vehicle applications (see more info [here](https://github.com/eclipse/kuksa.ide))
* Use different applications for various connected vehicle needs such as
  * [Direct Access API](https://github.com/eclipse/kuksa.invehicle/tree/master/direct-access-api)
  * [App-Manager](https://github.com/eclipse/kuksa.invehicle/tree/master/kuksa-appmanager)
  * [Appstore](https://github.com/eclipse/kuksa.cloud/tree/master/kuksa-appstore)
  * [BT-based OBD II](https://github.com/eclipse/kuksa.invehicle/tree/master/elm327-visdatafeeder)
  * [Traccar client](https://github.com/eclipse/kuksa.apps/tree/master/kuksa-traccar-client)
  * [Datalogger http](https://github.com/eclipse/kuksa.invehicle/tree/master/datalogger-http)
  * [Datalogger mqtt](https://github.com/eclipse/kuksa.invehicle/tree/master/datalogger-mqtt)
  * [VisDataFeeder](https://github.com/eclipse/kuksa.invehicle/tree/master/elm327-visdatafeeder)
  * [Kuksa-Hawkbit](https://github.com/eclipse/kuksa.invehicle/tree/master/kuksa-hawkbit)
  * [Remote-Access](https://github.com/eclipse/kuksa.invehicle/tree/master/remoteAccess)
  * [W3C-Visserver-API](https://github.com/eclipse/kuksa.invehicle/tree/master/w3c-visserver-api)
