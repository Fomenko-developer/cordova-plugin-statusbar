---
title: Statusbar
description: Control the device status bar.
---
<!---
# license: Licensed to the Apache Software Foundation (ASF) under one
#         or more contributor license agreements.  See the NOTICE file
#         distributed with this work for additional information
#         regarding copyright ownership.  The ASF licenses this file
#         to you under the Apache License, Version 2.0 (the
#         "License"); you may not use this file except in compliance
#         with the License.  You may obtain a copy of the License at
#
#           http://www.apache.org/licenses/LICENSE-2.0
#
#         Unless required by applicable law or agreed to in writing,
#         software distributed under the License is distributed on an
#         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#         KIND, either express or implied.  See the License for the
#         specific language governing permissions and limitations
#         under the License.
-->

# cordova-plugin-statusbar

> This is a original cordova status bar fork with a single additional property that allows to control the status bar background transparency.

## Installation

This installation method requires cordova 5.0+

    cordova plugin add https://github.com/Fomenko-developer/cordova-plugin-statusbar.git


Preferences
-----------

#### config.xml

-  __StatusBarOpacity__ (double, defaults to 1). Sets the statusbar opacity.

        <preference name="StatusBarOpacity" value="0.5" />