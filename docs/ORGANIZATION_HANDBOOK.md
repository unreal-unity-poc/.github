# unreal-unity-poc organization handbook

> Shared operating defaults for repositories maintained under **unreal-unity-poc**. Repository-local policy may strengthen these rules but should not silently weaken them.

## Mission

unreal-unity-poc maintains proof-of-concept interoperability, rendering, asset, networking, and workflow experiments across Unreal Engine and Unity. This `.github` repository is the canonical home for shared policy, reusable templates, community health files, and planning links.

## Repository contract

Each active proof of concept must document its objective, ownership, maturity, engine and plugin versions, supported platforms, reproducible setup and test commands, authoritative asset and interface formats, limitations, compatibility expectations, and GitHub Project/Linear links. Projects should also document coordinate and unit conventions, asset provenance and licensing, build pipelines, networking assumptions, performance targets, platform permissions, and cleanup or migration paths.

## Change workflow

1. Anchor work in an issue, Linear item, or documented experiment objective.
2. Keep branches and pull requests focused.
3. Explain the hypothesis, scope, platform impact, validation, compatibility, migration, and rollback.
4. Test clean import, build, runtime, asset round-trip, unsupported inputs, platform variation, performance, and failure paths as relevant.
5. Resolve conflicts semantically by reconstructing both sides' intent.
6. Prefer squash merges for focused work unless commit structure materially improves the experiment record.

## Evidence, security, and documentation

Pull requests should include exact engine/tool versions, reproducible commands, licensed fixtures, expected and observed behavior, screenshots or captures where useful, performance evidence, documentation updates, and CI or local-equivalent results. Never commit credentials, proprietary assets, restricted SDKs, signing material, or sensitive logs. Follow `SECURITY.md` for private reporting. Keep production caveats, asset rights, platform assumptions, and significant interoperability decisions explicit.

## Planning ownership

GitHub owns code, reviews, checks, releases, and delivery evidence. Linear owns priority, dependencies, sequencing, and cross-project planning. The organization GitHub Project is the cross-repository execution view; see `PROJECTS.md` for routing details.

## Organization health

- [ ] Profiles, descriptions, topics, and READMEs are current.
- [ ] Community health files and reusable issue/PR guidance are present.
- [ ] Engine/plugin versions, units, asset rights, build steps, limitations, and performance targets are documented.
- [ ] Required checks cover import/build/runtime, platform compatibility, asset integrity, and supply-chain risk.
- [ ] Stale experiments are archived or clearly marked.
- [ ] GitHub Project and Linear links resolve and reflect completed work.
