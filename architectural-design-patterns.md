# Architectural Design Patterns.

## General.
* [Architecture Design Patterns.](https://www.google.com/search?q=architecture+design+patterns&oq=archtecture+design+pa&aqs=chrome.1.69i57j0l7.14848j1j7&sourceid=chrome&ie=UTF-8)


## Cycle Breaker Pattern.
* Detect something is wrong
* Take temporary steps to avoid the situation getting worse.
* Deactivate the problem component so that it doesn't affect downstream components.

When does the circuit trip:
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
