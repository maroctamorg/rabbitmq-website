<!--
Copyright (c) 2007-2019 Pivotal Software, Inc.

All rights reserved. This program and the accompanying materials
are made available under the terms of the under the Apache License,
Version 2.0 (the "License”); you may not use this file except in compliance
with the License. You may obtain a copy of the License at

https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# .NET/C# RabbitMQ Client Library

    ## <a id="overview" class="anchor" href="#overview">Overview</a>

The RabbitMQ .NET client is an implementation of an AMQP 0-9-1 client
library for C# (and, implicitly, other .NET languages).

### <a id="series" class="anchor" href="#series">Release Series</a>

4.x and later release series of this library require .NET 4.5.1+ or .NET Standard 1.5+ implementation
(e.g. .NET Core 2.x).

The following table explains what RabbitMQ .NET client release series
targets what .NET standard (or .NET framework) version.

<table>
  <thead>
    <td>Library Release Series</td>
    <td>Required .NET Framework/Standard/Flavor Versions</td>
  </thead>

  <tr>
    <td>
      5.x
    </td>
    <td>
      .NET 4.5.1+ or a .NET Standard 1.5+ implementation (e.g. .NET Core 2.x)
    </td>
  </tr>

  <tr>
    <td>
      4.x
    </td>
    <td>
      .NET 4.5.1+ or a .NET Standard 1.5+ implementation (e.g. .NET Core 2.x)
    </td>
  </tr>

  <tr>
    <td>
      3.4.x
    </td>
    <td>
      .NET 3.5
    </td>
  </tr>

  <tr>
    <td>
      3.3.x
    </td>
    <td>
      .NET 2.0
    </td>
  </tr>
</table>

### <a id="licensing" class="anchor" href="#licensing">Licensing</a>

The library is [open-source](https://github.com/rabbitmq/rabbitmq-dotnet-client),
and is dual-licensed under the [the Apache License v2](https://www.apache.org/licenses/LICENSE-2.0) and [the Mozilla Public License v1.1](mpl.html).

This means that the user can consider the library to be licensed under any of the licenses from the list above.
For example, the user may choose the Apache Public License 2.0 and include this client into
a commercial product. Codebases that are licensed under the GPLv2 may choose GPLv2, and so on.

### <a id="licensing" class="anchor" href="#licensing">Licensing</a>

Recent versions of the library are exclusively [distributed via NuGet](https://www.nuget.org/packages/RabbitMQ.Client).


## <a id="distribution" class="anchor" href="#distribution">NuGet</a>

The most recent release of the RabbitMQ .NET client library is `5.1.2` ([on NuGet](https://www.nuget.org/packages/RabbitMQ.Client)).
Release notes can be found [on GitHub](https://github.com/rabbitmq/rabbitmq-dotnet-client/releases).


## <a id="documentation" class="anchor" href="#documentation">Documentation</a>

Please refer to the [API guide](/dotnet-api-guide.html). There's
also [an online API reference](http://rabbitmq.github.io/rabbitmq-dotnet-client/index.html).


## <a id="changelog" class="anchor" href="#changelog">Change log</a>

4.x and later release notes are [published to GitHub](https://github.com/rabbitmq/rabbitmq-dotnet-client/releases).


## <a id="binary-builds" class="anchor" href="#binary-builds">Binary Downloads</a>

Modern versions of this library (e.g. 4.x and 5.x) are distributed as a [NuGet package](https://www.nuget.org/packages/RabbitMQ.Client).

<table>
  <thead>
    <td>Description</td>
    <td>Download</td>
  </thead>

  <tr>
    <td class="desc">5.x NuGet package for .NET Core and .NET 4.5.1</td>
    <td><a href="https://www.nuget.org/packages/RabbitMQ.Client">RabbitMQ.Client NuGet package</a></td>
  </tr>
  <tr>
    <td class="desc">4.x NuGet package for .NET Core and .NET 4.5.1</td>
    <td><a href="https://www.nuget.org/packages/RabbitMQ.Client">RabbitMQ.Client NuGet package</a></td>
  </tr>
  <tr>
    <td class="desc">Legacy 3.x series binary builds</td>
    <td><a href="/releases/rabbitmq-dotnet-client">3.x builds</a></td>
  </tr>
</table>


## <a id="source-repository" class="anchor" href="#source-repository">Source Repository on GitHub</a>

The .NET RabbitMQ client library is [hosted and developed on GitHub](https://github.com/rabbitmq/rabbitmq-dotnet-client).

Please see the [.NET client build guide](/build-dotnet-client.html) for
instructions on compiling from source.

To clone the repo from GitHub:

<pre class="lang-bash">
git clone https://github.com/rabbitmq/rabbitmq-dotnet-client
</pre>

In order to compile or run the RabbitMQ .NET/C# client library,
please follow the [build instructions](/build-dotnet-client.html).


## <a id="signing" class="anchor" href="#signing">Strong Naming</a>

The client assembly is strong named. The public key token is 89e7d7c5feba84ce
and the public part of the signing key is

<pre class="lang-ini">
00240000048000009400000006020000002400005253413100040000010001008d20ec856aeeb8
c3153a77faa2d80e6e43b5db93224a20cc7ae384f65f142e89730e2ff0fcc5d578bbe96fa98a71
96c77329efdee4579b3814c0789e5a39b51df6edd75b602a33ceabdfcf19a3feb832f31d825416
8cd7ba5700dfbca301fbf8db614ba41ba18474de0a5f4c2d51c995bc3636c641c8cbe76f45717b
fcb943b5.
</pre>