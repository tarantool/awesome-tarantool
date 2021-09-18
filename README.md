# Awesome Tarantool

[![Awesome][awesome-badge]][awesome-url]
[![Tarantool][tarantool-badge]][tarantool-url]
[![License][license-badge]][license-url]

A curated list of delightful Tarantool [modules](#modules),
[connectors](#connectors) and other [resources](#resources).

## Contents

- [Packages](#packages)
- [Connectors](#connectors)
- [Resources](#resources)

## Packages

### Database

- [box](https://www.tarantool.io/en/doc/latest/book/box/) (builtin) -
  a high-performance multi-engine database.
- [queue](https://github.com/tarantool/queue) -
  a set of persistent in-memory queues.
- [vshard](https://github.com/tarantool/vshard) -
  automatic sharding and resharding.
- [memcached](https://github.com/tarantool/memcached) -
  memcached implementation on top of Tarantool.
- [expirationd](https://github.com/tarantool/expirationd) -
  data expiration with custom extensions.
- [avro-schema](https://github.com/tarantool/avro-schema) -
  Apache Avro schema tools for Tarantool.
- [gis](https://github.com/tarantool/gis) -
  a PostGIS-like module for Tarantool.

### Data Handling

- [json](https://www.tarantool.io/en/doc/latest/reference/reference_lua/json/)
  (builtin) - JSON encoder/decoder.
- [yaml](https://www.tarantool.io/en/doc/latest/reference/reference_lua/yaml/)
  (builtin) - YAML encoder/decoder.
- [msgpack](https://www.tarantool.io/en/doc/latest/reference/reference_lua/msgpack/)
  (builtin) - MsgPack encoder/decoder.
- [csv](https://www.tarantool.io/en/doc/latest/reference/reference_lua/csv/)
  (builtin) - CSV parser.

### Clients

- [net.box](https://www.tarantool.io/en/doc/latest/reference/reference_lua/net_box/)
  (builtin) - Tarantool client for Tarantool (WOW!).
- [mqtt](https://github.com/tarantool/mqtt) -
  MQTT client for Tarantool.
- [mysql](https://github.com/tarantool/mysql) -
  MySQL client for Tarantool.
- [pg](https://github.com/tarantool/pg) -
  PostgreSQL client for Tarantool.
- [curl](https://github.com/tarantool/curl) -
  libcurl bindings for Tarantool.
- [http](https://github.com/tarantool/http) -
  http client and server for Tarantool.

### GUI clients

- [tarantool-admin](https://github.com/basis-company/tarantool-admin) -
  web-based user interface.
- [ocelotgui](https://github.com/ocelot-inc/ocelotgui-tarantool) -
  primarily for Tarantool/SQL.
- [DataGrip](https://www.jetbrains.com/datagrip/) or [IntelliJ
  IDEA](https://www.jetbrains.com/idea/) with [Tarantool Database
  plugin](https://plugins.jetbrains.com/plugin/17422-tarantool-database) -
  cross platform database IDE that can do SQL queries.

### System

- [fiber](https://www.tarantool.io/en/doc/latest/reference/reference_lua/fiber/)
  (builtin) - cooperative multitasking and synchronization mechanisms.
- [socket](https://www.tarantool.io/en/doc/latest/reference/reference_lua/socket/)
  (builtin) - fiber-friendly socket I/O.
- [fio](https://www.tarantool.io/en/doc/latest/reference/reference_lua/fio/)
  (builtin) - fiber-friendly file I/O.
- [clock](https://www.tarantool.io/en/doc/latest/reference/reference_lua/clock/)
  (builtin) - high-precision timers.
- [log](https://www.tarantool.io/en/doc/latest/reference/reference_lua/log/)
  (builtin) - simple logger with support of syslog.
- [ljsyscall](https://github.com/tarantool-contrib/ljsyscall) -
  bindings for Unix syscall using FFI.

### Security

- [digest](https://www.tarantool.io/en/doc/latest/reference/reference_lua/digest/)
  (builtin) - popular hash functions.
- [luaossl](https://github.com/tarantool/luaossl) -
  the most comprehensive OpenSSL bindings.

### Miscellaneous

- [uuid](https://www.tarantool.io/en/doc/latest/reference/reference_lua/uuid/)
  (builtin) - Universally Unique Identifier library.

### Profilers

- [gperftools](https://github.com/tarantool/gperftools) -
  Lua bindings for Google Performance Tools CPU Profiler.

### Testing

- [tap](https://www.tarantool.io/en/doc/latest/reference/reference_lua/tap/)
  (builtin) - Test Anything Protocol implementation.

### Administration

- [Cartridge](https://github.com/tarantool/cartridge) -
  cluster manager.
- [console](https://www.tarantool.io/en/doc/latest/reference/reference_lua/console/)
  (builtin) - a text-based user interface.
- [prometheus](https://github.com/tarantool/prometheus) -
  Prometheus metric collector for Tarantool.
- [xlog](https://www.tarantool.io/en/doc/latest/reference/reference_lua/xlog/)
  (builtin) - a Lua module to read Tarantool's data files.
- [iproto-sniffer](https://github.com/dsamirov/tarantool-iproto-sniffer) -
  detects insert and replace and call protocol commands.

## Connectors

Tarantool connectors for various programming languages.

- [PHP PECL connector](https://github.com/tarantool/tarantool-php).
- [PHP pure connector](https://github.com/tarantool-php/client).
- [Python connector](https://github.com/tarantool/tarantool-python).
- [Java connector](https://github.com/tarantool/tarantool-java).
- [Go connector](https://github.com/tarantool/go-tarantool).
- [C# connector](https://github.com/progaudi/progaudi.tarantool).
- [Swift connector](https://github.com/tris-foundation/tarantool).
- [Erlang connector](https://github.com/stofel/taran).
- [C connector](https://github.com/tarantool/tarantool-c).
- [Nginx Upstream module](https://github.com/tarantool/nginx_upstream_module).
- [Crystal connector](https://github.com/vladfaust/tarantool-crystal).

## Resources

- [GitHub](https://github.com/tarantool) -
  GitHub umbrella for Tarantool-related projects.
- [Facebook](https://facebook.com/TarantoolDatabase) - official Facebook
  page.
- [Telegram](https://telegram.me/tarantool) - official Telegram channel
  (English).
- [Telegram/Russian](https://telegram.me/tarantoolru) - official Telegram
  channel (Russian).
- [Twitter](https://twitter.com/tarantooldb) - official Twitter account.

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-url]: https://awesome.re/
[tarantool-badge]: https://img.shields.io/badge/tarantool-2.6-blue.svg?style=flat
[tarantool-url]: https://www.tarantool.io
[license-badge]: https://img.shields.io/badge/License-CC--BY-orange.svg?style=flat
[license-url]: LICENSE.md
