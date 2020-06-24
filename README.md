# Software Design Pattern.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [Help.](#help)





## About.





## Documentation.





## Cycle Breaker Pattern.
* Detect something is wrong.
* Take temporary steps to avoid the situation getting worse.
* Deactivate the problem component so that it doesn't affect downstream components.
 
When does the circuit trip?
* Last n requests to consider for the decision.
* How many of those should fail?
* Timeout duration.

When does the circuit up-trip?
* How long after a circuit trip to try again?

Why cycle breaker.
* Failing fast.
* Fallback functionality.
* Automatic recovery.





## Bulkhead Pattern.





## Asynchronous Messaging Patterns.
* Message Queuing.
* Publish/Subscriber.




## Sidecar Pattern.
Pros.
* Language agnostics(polyglot).
* Protocol upgrade.
* Security.
* Tracing and monitoring. 
* Service Discovery.
* Caching.

Cons.   
* Complexity.
* Latency.





## Ambassador Pattern.





## Adapter Pattern.





## Decorator Pattern.





## Library Pattern.





## Help.
