# OpenRock-Config

Per-mod configuration, build-time-baked (bakeConfig) and runtime-mutable (readRuntimeConfig/writeRuntimeConfig via Capabilities), both validated against one declared schema.

Part of the [OpenRock](https://github.com/codex-alchemist-dev/OpenRock) Minecraft Bedrock mod-packaging ecosystem - a Codex Alchemist project, under Fireball Everything. Consumed as a real git submodule at `libs/config` in the main OpenRock repo, and directly `npm require`/`import`-able (real top-level CommonJS exports, esbuild-CJS/ESM-interop-compatible) by any mod's own build-time kernel registration or real in-game script.

## License

MPL-2.0. See [LICENSE](LICENSE).
