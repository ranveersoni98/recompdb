# Recompiled Ports Database

A community-maintained directory of recompiled game ports. People are making ports for all kinds of games and platforms, but information about them can be scattered and hard to keep track of. This project is a place to collect those projects in one organized, searchable format.

## What belongs here?

Add an entry for a recompiled port you made or found.

This is an index, not a place to host game files. Please don’t submit copyrighted game assets, executables, or other files you don’t have permission to share.

## Adding a port

1. Copy [`db/example.json`](db/example.json) and fill in the details.
2. Save it as a new, descriptive JSON file in `db/` (for example, `db/my-game-port.json`).
3. Set `port.ai_ported` to `true` if the project relied on AI-assisted or AI-generated porting work; otherwise use `false`.
4. Open a pull request. Keep the fields from the example; if a detail is unknown or doesn’t apply, use `null` or an empty array rather than guessing.

Pull requests that change database entries are automatically checked against [the database schema](.github/schemas/db-entry.schema.json). Please keep entries factual and link to authoritative project pages where possible. Update your entry when supported releases, target platforms, or compatibility changes.

## Licensing

 Database entries in `db/` are dedicated to the public domain under [CC0 1.0](LICENSE), so they can be reused without requiring attribution. This applies only to content contributors have the right to license; it does not grant rights to game assets, trademarks, or third-party material.

## The future

For now, this repository keeps the directory simple and easy to contribute to. Once it has around 20 entries, the plan is to turn the database into its own dedicated website.

## Disclaimer

This is an independent community project and is not affiliated with any game publisher, storefront, or platform holder. Game names and trademarks belong to their respective owners.