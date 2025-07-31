# Bugsink

Self-hosted, Sentry-SDK-compatible error tracking.

[The main repository](https://github.com/bugsink/bugsink) contains the Bugsink sourcecode.

The [Bugsink website](https://www.bugsink.com/) has more information about Bugsink, including [installation
instructions](https://www.bugsink.com/docs/installation/), general [documentation](https://www.bugsink.com/docs/),
and a [demo video](https://www.bugsink.com/blog/demo-video/).


![Screenshot: Bugsink UI showing a captured exception](https://www.bugsink.com/static/images/JsonSchemaDefinitionException.5e02c1544273.png)


## Supporting Repositories

**[helm-charts](https://github.com/bugsink/helm-charts)**  
Helm charts for deploying Bugsink in Kubernetes.

**[snappea](https://github.com/bugsink/snappea)**  
Minimal task queue. Uses SQLite and `inotify` instead of Redis or brokers.

**[monofy](https://github.com/bugsink/monofy)**  
Runs multiple long-lived processes in a single Docker container. Simple init alternative.

**[dsnrun](https://github.com/bugsink/dsnrun)**  
Run any Python script or module with a Sentry DSN. Designed for quick instrumentation.

**[verbose_csrf_middleware](https://github.com/bugsink/verbose_csrf_middleware)**  
Drop-in Django middleware to explain CSRF failures with full request context.

**[event-samples](https://github.com/bugsink/event-samples)**  
Sample error events used in development and testing.

**[spoils](https://github.com/bugsink/spoils/)**  
A lightweight collection of additional security checks for Bandit.

