# LeetOff runtimes

Pinned runtime archives that LeetOff builds download by URL and verify by SHA-256. Nothing here
runs on its own; each archive is pinned, by this repository's commit, in the LeetOff source that
consumes it. Earlier archives stay reachable at the commits that added them.

## csharp/csharp-runtime-fa0fc17d81add1bd.tar.gz

The C# playground runtime (LeetOff ADR 128): Roslyn 5.0.0 on the .NET 10 browser WebAssembly
runtime, with the .NET 10.0.10 reference assemblies, plus Roslyn's completion, signature help and
hover for the editor. Built with `pnpm csharp:runtime:build` (.NET SDK 10.0.302, packages
locked); the build is reproducible.

- SHA-256: `fa0fc17d81add1bd12e78cdd42935c23be4b57f233f89b1427eeac49402f4495`
- Bytes: 15389005
