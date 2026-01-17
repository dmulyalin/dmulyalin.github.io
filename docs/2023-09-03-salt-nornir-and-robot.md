---
title:  "Salt-Nornir and ROBOT"
summary: Let the robots run it
authors:
    - Denis Mulyalin
date: 2023-09-03
---

> 9 Sep 2023 by Denis Mulyalin

# Introduction

Starting with [release 0.19.0](https://github.com/dmulyalin/salt-nornir/releases/tag/0.19.0) 
Salt-Nornir got integration with [ROBOT Framework](https://robotframework.org/)
for processes automation.

ROBOT is a general purpose workflow execution engine primarily targeting
programmatic testing of the infrastructure. Integration with Salt-Nornir
allows to execute tasks and workflows expressed using powerful 
[ROBOT Framework DSL](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html) 
(Domain SPecific Language) once again extending the horizon of functionality
available to us for addressing network automation use cases.

Moreover, ROBOT Framework possesses significant 
[reporting capabilities](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#report-file)
all available for use with Salt-Nornir now.



# Test the network with Salt-Nornir and ROBOT

One of the main reasons for Salt-Nornir and ROBOT integration was ROBOT Framework 
reporting capabilities, especially in combination with `nr.test` execution results.

For example using this test suite:

```yaml

```




