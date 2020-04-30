# Deno

- [Deno](https://deno.land/)
- [GitHub](https://github.com/denoland/deno)

## Install

```bash
brew install deno
```

## Examples

Deno [example programs](https://deno.land/std/examples/)

## Welcome

```bash
deno https://deno.land/std/examples/welcome.ts
```

```bash
Download https://deno.land/std/examples/welcome.ts
Compile https://deno.land/std/examples/welcome.ts
Welcome to Deno 🦕
```

## TCP echo server

```bash
deno  --allow-net https://deno.land/std/examples/echo_server.ts

Listening on 0.0.0.0:8080
```

Run netcat. And send `hello world`.

```bash
nc localhost 8080
hello world
hello world
```
