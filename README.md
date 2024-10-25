<p align="right">
  <img width="32" height="32" src="./assets/taxi.png">
</p>

# Taxi

simple compiled language, and a compiler backend.

> [!CAUTION]
> Taxi is not finished, and wont be for a while. So expect breaking changes and big bugs, and missing features!

## Features

* Simple language and backend
* Fast enough
* Very capable

## Building

You must have a V compiler. see [vlang.io](https://vlang.io/)


```bash
v .         # for a simple build
v . -prod   # for a production build
```

## Samples 

#### Hello Taxi

```taxi

  import passanger.io

  fun main() {
    io.println("Hello, Taxi.")
  }

```