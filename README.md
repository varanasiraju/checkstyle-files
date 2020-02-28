scoverage-samples
==================

[![Build Status](https://travis-ci.org/scoverage/sbt-scoverage-samples.svg?branch=master)](https://travis-ci.org/scoverage/sbt-scoverage-samples)

A sample program for demonstrating scoverage's code coverage. This sample is an akka based mock quote engine. Note: This project deliberately doesn't have 100% coverage for demonstration purposes.

It uses:

* sbt scala samples
* sbt test1
* Scala Coverage Report
* Scalatest for unit tests
* Scoverage

To run:

```
sbt clean coverage test coverageReport
```

## License
```
This software is licensed under the Apache 2 license, quoted below.

Copyright 2014 Stephen Samuel

Licensed under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.