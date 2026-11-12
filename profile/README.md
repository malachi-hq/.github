# Malachi

Open source distributed log storage. A reimplementation of LinkedIn's NorthGuard.

**Status:** in development. Malachi is not yet recommended for production. Progress is tracked in the [issues](https://github.com/malachi-hq/malachi/issues).

## Start here

- [Website](https://malachi-hq.github.io/malachi/): what Malachi is and how it compares with other systems.
- [Repository](https://github.com/malachi-hq/malachi): source code, documentation and architecture notes.
- [Contributing](https://github.com/malachi-hq/malachi/blob/main/CONTRIBUTING.md): how to propose and review changes.
- [Security policy](https://github.com/malachi-hq/malachi/blob/main/SECURITY.md): report a vulnerability privately.

## Principles

- **Durable writes.** A produce is acknowledged only after a majority of replicas has the data on disk.
- **Replayable history.** Retention and offsets let consumers read past records again.
- **Verified in CI.** Fault, storage and upgrade drills run against real clusters in CI.

## License

Malachi is released under the [MIT License](https://github.com/malachi-hq/malachi/blob/main/LICENSE).
