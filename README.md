# Flamingo Analytics


## Introduction

Flamingo Analytics is a web application for analyzing log files.
Flamingo Analytics drastically simplifies log analytics through the following features.

## Feature

* Realtime Data Streaming
* Realtime Log Indexing
* Embedded Grok log patterns 
* Log Event Detecting using Complex Event Processing
* Log Mapper
* Log Explore
* Many sources, sinks
* Oozie Workflow Designer
* Spark Designer
* Notebook Style Analytics

## Build Status

[![Build Status](https://api.travis-ci.org/EXEM-OSS/flamingo-analytics.svg?branch=master)](https://travis-ci.org/EXEM-OSS/flamingo-analytics)

## License

[![Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-brightgreen.svg)](LICENSE)

## License Headers

### Java Header

```java
/*
 * Copyright (C) 2012-2016 the Flamingo Community.
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *      http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */
```

### JavaScript Header

```javascript
/*
 * Copyright (C) 2012-2016 the Flamingo Community.
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */
```


### XML Header

```xml
<!--
    Copyright (C) 2012-2016 the Flamingo Community.

    Licensed to the Apache Software Foundation (ASF) under one or more
    contributor license agreements.  See the NOTICE file distributed with
    this work for additional information regarding copyright ownership.
    The ASF licenses this file to You under the Apache License, Version 2.0
    (the "License"); you may not use this file except in compliance with
    the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->
```

## For Developer

### Spring Framework Profiles

* Development Mode : -Dspring.profiles.active=development
  Property Place Holder : /WEB-INF/config-dev.properties
* Production Mode : -Dspring.profiles.active=production
  Property Place Holder : /WEB-INF/config.properties

### Site Deployment

Open your Maven settings (~/.m2/settings.xml) and add the following server configuration:

```xml
<settings>
    <servers>
        <server>
            <id>github</id>
            <username>YOUR_GITHUB_USERNAME</username>
            <password>YOUR_PASSWORD</password>
        </server>
    </servers>
</settings>
```

Use following command for deploying site :

```
# mvn site:site
# mvn site:stage
# mvn site:deploy
```

## Community

* Facebook : https://www.facebook.com/groups/flamingo.workflow
* Slack : flamingo-dev-team.slack.com
* WIKI : http://confluence.exem-oss.org/display/FL/Flamingo
