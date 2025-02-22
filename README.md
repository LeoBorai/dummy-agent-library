<div align="center">
  <img align="center" width="180px" height="auto" src="./docs/hf-logo.png" />
  <h1 align="center">Dummy Agent Library</h1>
  <h4 align="center">🤗 Part of the Agent's Course from HuggingFace. Learn more at https://hf.co/learn/agents-course</h4>
</div>

## Motivation

Build a simple Agent Library to gasp the fundamentals learned in the AI Agents Architecture
course provided by Hugging Face.

## Run Locally

Build an run containers using `docker compose`

```bash
docker compose up --build notebook
```

> Using `Justfile` this is a matter of running `just build` and from
> there on `just dev`

After working you can release resources using:

```bash
docker compose down
```

> A [Justfile][1] is included!

[1]: https://just.systems
