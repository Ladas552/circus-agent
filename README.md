This repo has workflow that my [circus server](https://github.com/manic-systems/circus) connects to, and runs ephemeral runners in gha so I don't have to torture my pentium server to build rust and arm64.

Exists only because I don't want .github directory in my main nix repo, the config for my circus can be found at [Nix-Lands](https://tangled.org/did:plc:hi7tbaw6b3gnseqt4fkkiqxb) in file `circus.nix`
