# LeetOff runtimes

Pinned runtime archives that LeetOff builds download by URL and verify by SHA-256. Nothing here
runs on its own; each archive is pinned, by this repository's commit, in the LeetOff source that
consumes it. Earlier archives stay reachable at the commits that added them.

## csharp/csharp-runtime-b3afe62a102881aa.tar.gz

The C# runtime (LeetOff ADR 128): Roslyn 5.0.0 on the .NET 10 browser WebAssembly runtime, with
the .NET 10.0.10 reference assemblies, Roslyn's completion, signature help and hover for the
editor, and the judging library (`LeetOff.Judging`) that judged runs report through. Built with
`pnpm csharp:runtime:build` (.NET SDK 10.0.302, packages locked); the build is reproducible.

- SHA-256: `b3afe62a102881aaa97f878e962e720552f84588a97bd140827b9ede8158d290`
- Bytes: 15396173
