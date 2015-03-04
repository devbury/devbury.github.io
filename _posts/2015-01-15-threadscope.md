---
title: "threadscope"
bg: '#6db33f'
color: white
fa-icon: leaf
---

# spring-boot-starter-threadscope

A Spring Boot starter that sets up a "thread" scope similar to
[SimpleThreadScope](http://docs.spring.io/spring/docs/current/javadoc-api/org/springframework/context/support/SimpleThreadScope.html).
The difference being `spring-boot-starter-threadscope` supports destruction callbacks such as `@PreDestroy` and
propagates thread scoped beans to asynchronous threads.  Thread scope works in regular application contexts as
well as web application contexts.  It can be used to replace Spring's request scope.

## Activating

`spring-boot-starter-threadscope` is published to the [jcenter](https://bintray.com/bintray/jcenter) repository. To
use the starter, add the following dependency information to your project.

    <dependency>
        <groupId>devbury.threadscope</groupId>
        <artifactId>spring-boot-starter-threadscope</artifactId>
        <version>1.0.0</version>
    </dependency>

<a href="https://github.com/devbury/spring-boot-starter-threadscope"><i class="fa fa-github fa-4x"/></a>
