Segment display sample for Android Things
=========================================

This Android Things sample demonstrates how to use a segment display ht16k33
with an I2C backpack.


Pre-requisites
--------------

- Android Things compatible board
- Android Things SDK, currently offered through a private Maven repo. See
  instructions at [go/brillo-gradle-setup]
- Android Studio 2.2+
- Java 8
- 1 [segment display with I2C backpack](https://www.adafruit.com/product/1270)
- jumper wires
- 1 breadboard

Schematics
----------

![Schematics for Intel Edison](edison_schematics.png)
![Schematics for Raspberry Pi 3](rpi3_schematics.png)


Build and install
=================

On Android Studio, click on the "Run" button.

If you prefer to run on the command line, type

```bash
./gradlew installDebug
adb shell am start com.google.samples.segmentdisplay/.SegmentDisplayActivity
```

If you have everything set up correctly, the segment display will show "ABCD".


License
-------

Copyright 2016 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.