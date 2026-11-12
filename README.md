# LeetOff runtimes

Pinned runtime archives that LeetOff builds download by URL and verify by SHA-256. Nothing here
runs on its own; each archive is pinned in the LeetOff source that consumes it.

## csharp/csharp-runtime-c238bbcde7385597.tar.gz

The C# playground runtime (LeetOff ADR 128): Roslyn 5.0.0 on the .NET 10 browser WebAssembly
runtime, with the .NET 10.0.10 reference assemblies. Built with `pnpm csharp:runtime:build`
(.NET SDK 10.0.302, packages locked) from LeetOff commit 7818d88ef; the build is reproducible.

- SHA-256: `c238bbcde73855977a3ea3d3da094d40ba420731b1d83a5ee93ca957e2a81002`
- Bytes: 15380682
