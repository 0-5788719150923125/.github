Independent AI research, and the infrastructure it runs on. From the optimizer to the deployment, all of it public.

## praxis

**[repository](https://github.com/0-5788719150923125/praxis)** · **[live demo](https://arc.src.eco)**

A language-model research framework, written from scratch. More than fifty pluggable registries - attention, routing, memory, embeddings, losses, optimizers - so nearly every component swaps by CLI flag, and a new architecture is a configuration rather than a rewrite. Implements dozens of recent papers alongside original ones, and its checkpoints drop into HuggingFace unmodified.

![The Praxis training dashboard](https://raw.githubusercontent.com/0-5788719150923125/praxis/HEAD/static/dashboard.webp)

Around 140,000 lines of Python, near-daily since August 2024. Ships the dashboard above, a browser-tab distributed training swarm, and a LaTeX research paper generated from live code and run data, so the paper cannot drift from the source.

## ghost notes

**[repository](https://github.com/0-5788719150923125/ghost-notes)** · **[watch](https://youtu.be/-b2M7VSYIFU)**

An audiovisual framework in Godot, shaped as a notes app where a note becomes whatever is attached to it. With a song it is a spectral visualizer, procedural and deterministic, seeded by the audio's own fingerprint so the same song always draws the same show - with no generative model in the render path. With a script it is a reading, in a voice synthesized from first principles or by a small local neural one. With a brief it is a tarot episode made by AI agents, and with a clip it is a chroma-key effects editor. Any show exports to video. On a phone, it is a notes app and nothing more.

Around 160,000 lines of GDScript, shaders and Python, built from registries the same way praxis is: 55 scenes, 22 visual layers, 8 physics forces, 21 masking effects, and media that change what the show is carried on - full frame, or the panels of a comic book flown over by a perspective camera. Every registry documents itself, and Godot is the only thing to install; the app provisions the rest.

## platformer

**[repository](https://github.com/0-5788719150923125/platformer)**

A Terraform framework for multi-account, multi-region infrastructure. Services enable declaratively through composable YAML state fragments, and consumer modules declare what they need while a root orchestrator wires the providers - dependency inversion, in HCL. Around 20,000 lines across 27 modules, with a native test suite and its own generated docs.

Distilled from production experience running thousands of EC2 instances across a global medical-imaging network. An archivist module scrubs and versions the codebase on every apply, which is how the repository was safely opened.

## also here

- **[nutube](https://github.com/0-5788719150923125/praxis/tree/main/axis/nutube)** - a video client for Android whose recommendation algorithm runs on the device. Every card names the reason it surfaced.
- **[src.eco](https://src.eco)** - a peer-to-peer communications platform and AI sandbox, live since 2020.
- **[ode](https://github.com/0-5788719150923125/ode)** - language models from scratch in JavaScript. Transformers, RNNs and state-space models, with hand-rolled optimizers, samplers and tokenizers.
- **[vtx](https://github.com/0-5788719150923125/vtx)** - a declarative, Dockerized platform for training small models across architectures, distributed over Petals and Hivemind.

Two more live here without being public. **rift** is a workshop for books: one directory per book, holding the manuscript, its metadata, and the built PDF, EPUB and cover. **cv** is a data-driven resume owned end to end, one YAML file in and one static page out.

---

**[Discord](https://discord.gg/bp3SuFae5M)** · **[YouTube](https://youtube.com/@The-Arc)**
