# LeetOff runtimes

Pinned runtime archives that LeetOff builds download by URL and verify by SHA-256. Nothing here
runs on its own; each archive is pinned, by this repository's commit, in the LeetOff source that
consumes it. Earlier archives stay reachable at the commits that added them.

## csharp/csharp-runtime-e709bef5596af3d7.tar.gz

The C# playground runtime (LeetOff ADR 128): Roslyn 5.0.0 on the .NET 10 browser WebAssembly
runtime, with the .NET 10.0.10 reference assemblies, plus Roslyn's completion, signature help and
hover for the editor. Built with `pnpm csharp:runtime:build` (.NET SDK 10.0.302, packages
locked); the build is reproducible.

- SHA-256: `e709bef5596af3d71f768b43bf2729aee34998d06e157efe62a62ddb58cc4748`
- Bytes: 15388970
