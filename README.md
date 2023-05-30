<a href="https://www.taoensso.com/clojure" title="More stuff by @ptaoussanis at www.taoensso.com">
<img src="https://www.taoensso.com/taoensso-open-source.png" alt="Taoensso open-source" width="480""/></a>

# Sente

## Realtime web comms for Clojure/Script

**Sente** is a small client+server library that makes it easy to build **realtime web applications** with Clojure + ClojureScript.

Loosely inspired by [Socket.IO](https://socket.io/), it uses **core.async**, **WebSockets**, and **Ajax** under the hood to provide a simple high-level API that enables **reliable, high-performance, bidirectional communications**.

![Hero](https://raw.githubusercontent.com/ptaoussanis/sente/master/hero.jpg "Source: http://almostsente.tumblr.com/")

> **Sen-te** (先手) is a Japanese [Go](https://en.wikipedia.org/wiki/Go_(game)) term used to describe a play with such an overwhelming follow-up that it demands an immediate response, leaving its player with the initiative.

## Latest releases

- 2023-05-30: `1.18.0-RC1` (dev): [release notes](https://github.com/ptaoussanis/sente/releases/tag/v1.18.0-RC1) | [Clojars](https://clojars.org/com.taoensso/sente/versions/1.18.0-RC1)
- 2022-06-13: `1.17.0`  (stable): [release notes](https://github.com/ptaoussanis/sente/releases/tag/v1.17.0) | [Clojars](https://clojars.org/com.taoensso/sente/versions/1.17.0)

## Features
 * **Bidirectional a/sync comms** over **WebSockets** with **auto Ajax fallback**
 * **It just works**: auto keep-alives, buffering, protocol selection, reconnects
 * Efficient design with transparent event batching for **low-bandwidth use, even over Ajax**
 * Send **arbitrary Clojure vals** over [edn](https://github.com/edn-format/edn
) or [Transit](https://github.com/cognitect/transit-clj) (JSON, MessagePack, etc.)
 * **Tiny API** (see the [wiki][] for details)
 * Automatic, sensible support for users connected with **multiple clients** and/or devices simultaneously
 * Realtime info on **which users are connected** over which protocols
 * Standard **Ring security model**: auth as you like, HTTPS when available, CSRF support, etc.
 * Support for [several popular web servers](https://github.com/ptaoussanis/sente/tree/master/src/taoensso/sente/server_adapters), [easily extended](https://github.com/ptaoussanis/sente/blob/master/src/taoensso/sente/interfaces.cljc) to other servers.

## Resources
1. [Wiki][wiki] - **community docs** (new!) 👈
1. [Release info][] - releases and changes
1. [API docs][] - auto-generated API docs
1. [GitHub issues][] - for support requests, contributions, etc.

## Funding this work

Please see [here][funding] if you'd like to help support continued my [open-source work][], thank you! 🙏 - Peter

## License

Copyright &copy; 2014-2023 [Peter Taoussanis][], licensed under [EPL 1.0][] (same as Clojure).

[wiki]: ../../wiki
[Release info]: ../../releases
[API docs]: http://ptaoussanis.github.io/sente/
[GitHub issues]: ../../issues
[funding]: https://taoensso.com/clojure/backers
[EPL 1.0]: LICENSE
[Peter Taoussanis]: https://www.taoensso.com
[open-source work]: https://www.taoensso.com/clojure