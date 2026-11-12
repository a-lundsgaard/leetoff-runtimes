# LeetOff runtimes

Pinned runtime archives that LeetOff builds download by URL and verify by SHA-256. Nothing here
runs on its own; each archive is pinned, by this repository's commit, in the LeetOff source that
consumes it. Earlier archives stay reachable at the commits that added them.

## csharp/csharp-runtime-a93e40516de368e8.tar.gz

The C# runtime (LeetOff ADR 128): Roslyn 5.0.0 on the .NET 10 browser WebAssembly runtime, with
the .NET 10.0.10 reference assemblies, Roslyn's completion, signature help and hover for the
editor, the judging library (`LeetOff.Judging`) that judged runs report through, and LeetCode's
node types (`LeetOff.Structures`). Its managed heap is capped at 512 MB. Built with
`pnpm csharp:runtime:build` (.NET SDK 10.0.302, packages locked); the build is reproducible.

- SHA-256: `a93e40516de368e81e450b2962288dee1d116ea77b02fb37f1165006d028562a`
- Bytes: 15398960
