# Skua

A local NVR with realtime object detection for IP cameras.

Skua is a fork of [Frigate](https://github.com/blakeblackshear/frigate). We
forked because we build software with AI and want a project that says so
openly. LLMs are better at coding and architecture than we are, and it's
silly to pretend otherwise. Use whatever tools make you productive, and send
the result.

**Contributions are highly appreciated**, AI-assisted or not. See
[CONTRIBUTING.md](CONTRIBUTING.md) and our [AI policy](AI_POLICY.md).

## Status

Skua currently tracks Frigate's `dev` branch plus our own fixes. The rename
is in progress: the code, UI and docs still say "Frigate" in many places.
Until that's done we publish no builds; run it from source.

Fixes so far:

- The live view no longer leaks a JSMpeg player (canvas, WebGL context and
  socket) every time a camera tile unmounts.

## Upstream

Frigate is developed by Frigate, Inc. and its contributors. Its
documentation at https://docs.frigate.video applies to Skua as well for now.

## License

MIT, see [LICENSE](LICENSE). The original Frigate copyright notice is kept as
the license requires.

"Frigate", "Frigate NVR", "Frigate+" and the Frigate logo are trademarks of
Frigate, Inc. Skua is not affiliated with or endorsed by Frigate, Inc.
