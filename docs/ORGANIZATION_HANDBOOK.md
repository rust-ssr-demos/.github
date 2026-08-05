# rust-ssr-demos organization handbook

> Shared operating defaults for repositories maintained under **rust-ssr-demos**. Repository-local policy may strengthen these rules but should not silently weaken them.

## Mission

rust-ssr-demos maintains Rust server-side-rendering examples, reference implementations, and interoperability demonstrations. This `.github` repository is the canonical home for shared policy, reusable templates, community health files, and planning links.

## Repository contract

Each active demo must document its learning objective, framework and version, maturity, prerequisites, reproducible run and test commands, deployment assumptions, compatibility expectations, and GitHub Project/Linear links. Demos should clearly separate production guidance from intentionally simplified teaching code and document hydration, routing, state, caching, error, security, accessibility, and shutdown behavior.

## Change workflow

1. Anchor work in an issue, Linear item, or documented maintenance objective.
2. Keep branches and pull requests focused.
3. Explain the teaching or reference value, scope, validation, compatibility impact, and rollback.
4. Test clean setup, build, server rendering, hydration, navigation, invalid input, failure, and shutdown paths as relevant.
5. Resolve conflicts semantically by reconstructing both sides' intent.
6. Prefer squash merges for focused work unless preserving commit history materially improves the example.

## Evidence, security, and documentation

Pull requests should include exact setup commands, supported toolchain versions, expected and observed results, screenshots or traces when useful, documentation updates, and CI or local-equivalent evidence. Never commit credentials or sensitive data. Follow `SECURITY.md` for private reporting. Pin dependencies where reproducibility matters and keep examples readable, executable, accessible, and explicit about shortcuts and production caveats.

## Planning ownership

GitHub owns code, reviews, checks, releases, and delivery evidence. Linear owns priority, dependencies, sequencing, and cross-project planning. The organization GitHub Project is the cross-repository execution view; see `PROJECTS.md` for routing details.

## Organization health

- [ ] Profiles, descriptions, topics, and READMEs are current.
- [ ] Community health files and reusable issue/PR guidance are present.
- [ ] Framework, Rust toolchain, setup, learning objective, and production caveats are explicit.
- [ ] Required checks cover build, SSR, hydration, accessibility, compatibility, and supply-chain risk.
- [ ] Stale demos are archived or clearly marked.
- [ ] GitHub Project and Linear links resolve and reflect completed work.
