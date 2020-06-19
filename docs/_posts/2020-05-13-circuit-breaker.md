---
title: '#1: Circuit Breaker'
permalink: /1
tags: resilience4j hystrix polly akka ruby
description: Circuit breaker is a design pattern that prevents cascading failures in distributed systems.
---

<a class="spreaker-player" href="https://www.spreaker.com/show/around-it-in-256-seconds" data-resource="episode_id=27523620" data-width="100%" data-height="350px" data-theme="dark" data-playlist="show" data-playlist-continuous="true" data-autoplay="false" data-live-autoplay="false" data-chapters-image="true" data-episode-image-position="left" data-hide-logo="false" data-hide-likes="false" data-hide-comments="false" data-hide-sharing="false" data-hide-download="true">Listen to "Around IT in 256 seconds" on Spreaker.</a>

Circuit breaker is a design pattern that prevents cascading failures in distributed systems.
More details: [https://microservices.io/patterns/reliability/circuit-breaker.html](https://microservices.io/patterns/reliability/circuit-breaker.html) and [https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker).

## Circuit breaker implementations:

* [Resilience4j](https://github.com/resilience4j/resilience4j) (Java)
* [Polly](http://www.thepollyproject.org/) (.NET)
* [rubyist/circuitbreaker](https://github.com/rubyist/circuitbreaker) (Go)
* [Scala/Akka](https://doc.akka.io/docs/akka/current/common/circuitbreaker.html)
* [circuit-breaker-js](https://github.com/yammer/circuit-breaker-js) (JavaScript)


This episode was originally twice as long.
If you wish to hear full, director's cut version, check out [my mailing list](https://256.nurkiewicz.com/newsletter).
I will also notify you about new episodes and add some extra content.

## Also listen to

* [#2: Service Mesh](2) - often includes circuit breaker so you don't have to include it yourself in your application

{% include newsletter-input.md %}