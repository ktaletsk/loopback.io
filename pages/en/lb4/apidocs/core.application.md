---
lang: en
title: 'API docs: core.application'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.core.application.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/core](./core.md) &gt; [Application](./core.application.md)

## Application class

Application is the container for various types of artifacts, such as components, servers, controllers, repositories, datasources, connectors, and models.

<b>Signature:</b>

```typescript
export declare class Application extends Context implements LifeCycleObserver 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./core.application._constructor_.md) |  | Constructs a new instance of the <code>Application</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [options](./core.application.options.md) |  | <code>ApplicationConfig</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [component(componentCtor, name)](./core.application.component.md) |  | Add a component to this application and register extensions such as controllers, providers, and servers from the component. |
|  [controller(controllerCtor, name)](./core.application.controller.md) |  | Register a controller class with this application. |
|  [getServer(target)](./core.application.getserver.md) |  | Retrieve the singleton instance for a bound server. |
|  [lifeCycleObserver(ctor, name)](./core.application.lifecycleobserver.md) |  | Register a life cycle observer class |
|  [server(ctor, name)](./core.application.server.md) |  | Bind a Server constructor to the Application's master context. Each server constructor added in this way must provide a unique prefix to prevent binding overlap. |
|  [servers(ctors)](./core.application.servers.md) |  | Bind an array of Server constructors to the Application's master context. Each server added in this way will automatically be named based on the class constructor name with the "servers." prefix. |
|  [service(cls, name)](./core.application.service.md) |  | Add a service to this application. |
|  [setMetadata(metadata)](./core.application.setmetadata.md) |  | Set application metadata. <code>@loopback/boot</code> calls this method to populate the metadata from <code>package.json</code>. |
|  [start()](./core.application.start.md) |  | Start the application, and all of its registered observers. |
|  [stop()](./core.application.stop.md) |  | Stop the application instance and all of its registered observers. |


