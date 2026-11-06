# BMO evidence study

Reproducible completion contract, conventional-cache comparison, public trajectory audit, and synthetic investigation-selection study.

## Release v0.1.0

The complete source and retained results are distributed in the release archive `bmo-evidence-paper-v0.1.0.zip`. This repository is its release landing page. Extract the archive and run the top-level reproduction command from the extracted directory:

```sh
python3 reproduce.py --download
```

Python 3.10 or newer and the standard library suffice. The public trajectory audit downloads hash-pinned upstream records; it never executes recorded agent commands or reruns their task grading. Without `--download` or `--inputs`, the finite, cache, and acquisition studies run and the public audit is explicitly skipped.

Archive SHA-256:

```text
99598ba415caedfd3a1bede531a237cc5d91811fa3255e50b959ba94f5a775ae
```

## Results and limits

- In 299,593 finite histories with exact supplied dependencies, selective reuse reduced terminal logical calls by 37.8% and total logical calls by 7.0% relative to complete-context matching. These are check counts, not measured time or repair improvements.
- A conventional action cache with equivalent keys, scheduling, and latest-result retention matched the selective policy in all 898,779 comparisons. Full historical retention improved the same counts further. There is no demonstrated BMO-specific caching advantage.
- The eight-trajectory public audit is descriptive. It does not establish safe reuse, wasted checks, stale-pass acceptance, or net time saved.
- ACQ-001 is an executed supplied-model synthetic acquisition study with wins and losses. It does not generate hypotheses or measure real repository repair. The later post-hoc exact-adaptive supplement is outside v0.1.0.
- The practical Gemma protocol remains UNFROZEN, with zero model runs. Identity-comparison tests do not establish atomic finalization or production race safety.

## Scope and license

The archive's `LICENSE_SCOPE.md`, `LICENSE`, `NOTICE`, and `THIRD_PARTY_NOTICES.md` govern the scoped Apache-2.0 grant to covered original material. The license and scope are also copied here for convenience. Third-party upstream materials retain their own terms and are fetched separately where required.

All 79 study/component/program files are byte-identical to the approved unified v3 research artifact. The licensed release changed root licensing and release-administration documents only. Its original prepared full-source Git identity is archival provenance; the GitHub landing-page commit is a separate publication record.

The author-review packet, manuscript, private references, private repository history, post-hoc supplement, and raw third-party source captures are not included in this public release.

Prepared 6 November 2026 UTC. Historical draft labels and frozen UTC records remain unchanged inside the archive.
