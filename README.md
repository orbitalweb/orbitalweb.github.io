
![Logo](crystal.webp)

## "What will the web look like in 10 years?".

We believe web interfaces will start to blend with the real world, that there will be virtual actions or verbs attached to everyday objects, and that the browser as your user-agent will in some ways invert the current display architectures that we are used to. Instead of each app rendering to a separate page your user agent will arbitrate and filter many apps attempting to render to the same view. We believe this will create new challenges for accessibility and for filtering and sense-making and that this needs to be explored.

At a foundation level this work leverages and is highly indebited to the work of many existing technologies. We're using Servo, Rust and Cargo to support durable persistent apps on the client, and as a result benefit from emerging standards such as WebGPU, WebXR, and process and filesystem sandboxing. Our interest here is supporting durable persistent first class apps within the browser; so we are creating a new persistence model for rich apps.

Beyond this we see an opportunity to make data objects into first class citizens. Public ledgers and services such as Metamask allow for self signed identity, and help reduce the need for separate accounts and passwords on each service. We also see a role for social trust graphs similar to Keybase in order to help filter and score content and to keep out bad actors. We also see https://solidproject.org/ as an important capability we want to provide.

We distill this down into these capabilities:

<a class="button" href="https://orbitalweb.github.io/philosophy/2020/02/10/persistent-web-apps.html" >Persistent Web Agents</a>
<a class="button" href="https://orbitalweb.github.io/philosophy/2021/02/15/why-xr.html" >3D Forward Design</a>
<a class="button" href="https://orbitalweb.github.io/philosophy/2021/02/05/self-sovereign-identity.html" >Identity and Trust</a>

For more thoughts also please see our [vision statement](logs/20201001Vision.md)

## Roadmap

Please see our [roadmap document](logs/20210115RoadMap.md)

## Chat with us on discord

Please join us on [Discord](https://discord.gg/eRsBbcXjzX)

## Downloads

Stay Tuned!

## Rust

We're working with Rust, not just because we're partial to Mozilla's groundbreaking work, but because the memory management model reduces many of the risks for building complex projects. It's a modern grammar with an intelligent packaging system, avoiding many of the ambiguities and risks of other grammars. Much as we're also fond of Javascript and C# and other grammars - this is a clear choice. As well the Internet community around Rust is a virtuous circle of people who care about other people.

## License

All the work here is published under The Apache Open Source License. This is a permissive free software license written by the Apache Software Foundation. It allows users to use the software for any purpose, to distribute it, to modify it, and to distribute modified versions of the software under the terms of the license, without concern for royalties. Please see the attached license file in this folder. We're supporting both Apache 2.0 and MIT licenses following the Rust philosophy, arguably avoiding risks of patent capture.

## Code of Conduct

Please see our [Code of Conduct](CODE_OF_CONDUCT.md)
