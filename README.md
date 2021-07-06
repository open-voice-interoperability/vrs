# Voice Registry System (VRS)

This repository contains the VRS source code, swagger.

# Overview and Problem Context

VRS documentation, please see [here](https://github.com/open-voice-network/docs/blob/main/components/voice_registry_system.md)

# Prerequisites

## Required

- Download [Rust](https://www.rust-lang.org/tools/install)
- Framework: Rockets
- ORM: Diesel

## Optional

- An API Explorer ([Postman](https://www.postman.com/downloads) or [Insomnia](https://insomnia.rest/download))
- Install [cargo watch](https://crates.io/crates/cargo-watch). Cargo Watch watches over your project's source for changes, and runs Cargo commands when they occur. It is like a nodemon

```sh
cargo install cargo-watch
```

## Build

```sh
cargo run
```

OR

```sh
cargo watch -x run
```

## Docker build and run

```sh
docker build --progress=plain --tag open-voice-network/vrs:0.0.1 .
docker run -p 8000:8000 open-voice-network/vrs:0.0.1
```

Once the VRS container is running, check out the following URLs:

- <localhost:8000>
- <localhost:8000/records>
