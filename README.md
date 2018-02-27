[![Download](https://api.bintray.com/packages/apptuitai/maven/metrics-apptuit/images/download.svg)](https://github.com/ApptuitAI/metrics-apptuit/releases/latest)
[![Build Status](https://img.shields.io/travis/ApptuitAI/metrics-apptuit.svg)](https://travis-ci.org/ApptuitAI/metrics-apptuit)
[![Sonar Cloud](https://sonarcloud.io/api/badges/gate?key=ai.apptuit:metrics-apptuit)](https://sonarcloud.io/dashboard?id=ai.apptuit:metrics-apptuit)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/00757015e04e4dd7bf892819420ec890)](https://www.codacy.com/app/ApptuitAI/metrics-apptuit)
[![Code Coverage](https://img.shields.io/codecov/c/github/ApptuitAI/metrics-apptuit.svg)](https://codecov.io/gh/ApptuitAI/metrics-apptuit)
[![License](https://img.shields.io/github/license/ApptuitAI/metrics-apptuit.svg)](https://github.com/ApptuitAI/metrics-apptuit/blob/master/LICENSE)

# metrics-apptuit

A reporter to send metrics from [dropwizard/codahale metrics](http://metrics.dropwizard.io/) library to Apptuit.AI.

## Usage

If your application uses [Dropwizard metrics](http://metrics.dropwizard.io/) library to collect metrics, follow the **[Dropwizard metrics integration guide](https://github.com/ApptuitAI/metrics-apptuit/wiki/UsageDropwizard)** to configure Dropwizard to publish the metrics to Apptuit.AI.

If your application uses a custom/different library to collect metrics (instead of Dropwizard metrics), you could use the `ApptuitPutClient` to publish metrics directly to Apptuit. Refer the **[Put client reference guide](https://github.com/ApptuitAI/metrics-apptuit/wiki/UsagePutClient)** for help publishing metrics from your code to Apptuit.AI.


## LICENSE

```
Copyright 2017 Agilx, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
