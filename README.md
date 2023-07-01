<!---
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
# ANTLR 4.13.0 Issue JDK 21 EA

[![Apache License, Version 2.0, January 2004](https://img.shields.io/github/license/apache/maven.svg?label=License)][license]
[![Main](https://github.com/khmarbaise/issue-antlr-4.13.0/actions/workflows/main.yaml/badge.svg)](https://github.com/khmarbaise/issue-antlr-4.13.0/actions/workflows/main.yaml)[![Issues](https://img.shields.io/github/issues/khmarbaise/rpn-calculator)](https://github.com/khmarbaise/rpn-calculator/issues)
[![Issues Closed](https://img.shields.io/github/issues-closed/khmarbaise/issue-antlr-4.13.0)](https://github.com/khmarbaise/issue-antlr-4.13.0/issues?q=is%3Aissue+is%3Aclosed)

Example project for compiler WARNING created during build with JDK 21 EA build.

Related to issue: https://github.com/antlr/antlr4/issues/4341

```text
[INFO] --- compiler:3.11.0:compile (default-compile) @ issue-antlr-4.13.0 ---
[INFO] Changes detected - recompiling the module! :source
[INFO] Compiling 4 source files with javac [debug release 21] to target/classes
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[95,50] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[174,70] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[187,67] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[199,69] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[217,76] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[231,68] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[241,68] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[253,75] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[263,66] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[275,72] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[287,75] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprParser.java:[299,72] possible 'this' escape before subclass is fully initialized
[WARNING] ../issue-antlr-4.13.0/target/generated-sources/antlr4/com/soebes/rpn/grammar/ExprLexer.java:[88,49] possible 'this' escape before subclass is fully initialized
```

[license]: https://www.apache.org/licenses/LICENSE-2.0
