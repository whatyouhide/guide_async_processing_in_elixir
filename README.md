# Asynchronous Processing in Elixir 🏃

![Cover image of some abstract lights][cover-image]

This is a short interactive guide to asynchronous data processing in Elixir. It
uses [Livebook][livebook] to show interactive Elixir snippets that you can run
on your own machine.

## How Do I Use This?

There are a handful of livebooks in this guide. Using the badges below, you can
import them to your computer and run and explore them there. My recommendation
is to use the Livebook desktop app that you can find [on its website][livebook].

### 01 — Processes

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwhatyouhide%2Fguide_async_processing_in_elixir%2Fmain%2F01-processes.livemd)

In this livebook we talk about the basics of processes and message passing.

### 02 — Tasks

Here, we talk about the `Task` abstraction that ships in Elixir's standard
library.

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwhatyouhide%2Fguide_async_processing_in_elixir%2Fmain%2F02-tasks.livemd)

### 03 — GenStage

[GenStage] is an Elixir library maintained by the Elixir core team. It lets you
build pipelines of stages through which events flow.

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwhatyouhide%2Fguide_async_processing_in_elixir%2Fmain%2F03-genstage.livemd)

### 04 — Flow

[Flow] is another Elixir library maintained by the core team. It builds on top
of GenStage to provide an API similar to `Enum` and `Stream`, but for parallel
data processing.

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwhatyouhide%2Fguide_async_processing_in_elixir%2Fmain%2F04-flow.livemd)

### 05 — Broadway

[Broadway] lets you build declarative data ingestion and processing pipelines.
It supports several sources (RabbitMQ, Kafka, AWS SQS, and more).

[![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwhatyouhide%2Fguide_async_processing_in_elixir%2Fmain%2F05-broadway.livemd)

## License

See [the license file](./LICENSE.txt).

"Social preview" photo by [Bofu Shaw](https://unsplash.com/@hikeshaw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/speed?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).

[livebook]: https://livebook.dev
[GenStage]: https://github.com/elixir-lang/gen_stage
[Flow]: https://github.com/elixir-lang/flow
[Broadway]: https://elixir-broadway.org
[cover-image]: https://user-images.githubusercontent.com/3890250/182093532-159e5bcc-dcd7-40d7-9030-da914f3db0bb.jpg
