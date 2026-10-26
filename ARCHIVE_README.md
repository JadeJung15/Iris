# upstream-archive

Snapshot of dolidolih/Iris taken 2026-10-26 (KST).

- Release backup: metadata and all 68 assets for 19 releases, unchanged by the PR repair.
- Issues: the existing listing is preserved; comments are not archived.
- Pull requests: all 119 PRs in open and closed states, collected through the final empty page and refreshed 2026-10-26T15:25:03Z. The export preserves full titles/bodies and the previous selected-metadata schema.
- PR comments, review comments, reviews, diffs/patches and PR head code snapshots are not included. This is not a complete discussion-history backup.

Archive contents: `releases/<tag>/release.json` and assets; `discussions/issues.json`; `discussions/pulls.json`.
The archive is stored as `archive.tar.b64.partNN`. Run `bash restore.sh` from this branch's root to reconstruct and extract it.

`BACKUP_MANIFEST.json` records the collection scope, pagination, counts, byte sizes, SHA-256 digests and Git blob IDs. The PR repair changes only the final archive part; all other archive payload files are byte-identical.
