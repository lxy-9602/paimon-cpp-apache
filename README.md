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
-->

# Apache Paimon C++ Client

A C++ client library for [Apache Paimon](https://paimon.apache.org/) — a streaming data lake platform that supports high-speed data ingestion, changelog tracking, and efficient real-time analytics.

## Overview

This project provides a native C++ SDK for reading and writing Apache Paimon tables, enabling high-performance integration for C/C++ applications without JVM dependencies.

## Features (Planned)

- Read Paimon tables (primary-key tables and append-only tables)
- Write to Paimon tables with streaming and batch modes
- Schema evolution support
- Snapshot management and time travel queries
- Filesystem and object storage access (local, HDFS, S3, OSS)

## Requirements

- C++17 or later
- CMake 3.16+

## Building

```bash
mkdir build && cd build
cmake ..
make -j$(nproc)
```

## Contributing

We welcome contributions! Please see the [Apache Paimon community page](https://paimon.apache.org/community/contribution-guide/) for guidelines.

## License

This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
