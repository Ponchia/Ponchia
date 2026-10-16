# Zeno Trevisan · Ponchia

Cloud architect and platform engineer working on Kubernetes, cloud infrastructure, and open-source tools for developers and the web.

## Choose a starting point

| What you need | Project | Try it |
| --- | --- | --- |
| Build a dashboard or developer interface with ordinary HTML | **[Bronto UI](https://github.com/Ponchia/bronto-ui)** — CSS-first components, tokens and optional JavaScript behaviors; available on npm | [Interactive examples](https://ponchia.github.io/bronto-ui/examples/) |
| Add explanatory notes to an existing chart or diagram | **[Bronto Annotations](https://github.com/Ponchia/bronto-annotations)** — headless placement and connector routing with optional renderers; stable npm release and a separate 0.7 candidate | [Placement playground](https://ponchia.github.io/bronto-annotations/#playground) |
| Check responsive relationships that pixel or overflow checks miss | **[Bronto Layout](https://github.com/Ponchia/bronto-layout)** — local CLI and explicit layout contracts; experimental GitHub beta | [A controlled alignment regression](https://github.com/Ponchia/bronto-layout/blob/main/docs/portfolio-regression-case-study.md) |
| Keep diagrams, charts and timelines editable across views | **[Bronto Visual Models](https://github.com/Ponchia/bronto-visual-models)** — identified content, guarded edits and optional views; installable GitHub beta | [Live demo](https://ponchia.github.io/bronto-visual-models/) · [First model](https://github.com/Ponchia/bronto-visual-models/blob/main/docs/getting-started.md) |
| Connect Vaultwarden or Bitwarden Password Manager vault items to Kubernetes Secrets | **[Vaultwarden ESO Provider](https://github.com/Ponchia/vaultwarden-eso-provider)** — Rust webhook provider for External Secrets Operator; release candidate, with Cloud acceptance still pending | [Compatibility and limits](https://github.com/Ponchia/vaultwarden-eso-provider/blob/main/docs/compatibility.md) |
| Explore perception and response timing in the browser | **[Sense6](https://github.com/Ponchia/sense6)** — five recreational experiments with a local journal; device-relative results, not medical tests | [Try Sense6](https://sense6.net/en/) |

## Bronto in practice

Bronto UI's own website uses Bronto Layout in its required CI: the site owns its
responsive contracts, and intentional overflow and alignment regressions must
fail before deployment. Visual Models has a separate installed-package example
that demonstrates preview, replay, stale-edit refusal and undo without a server.

[Read the integration case study and reproduce the checks](docs/bronto-in-practice.md).
These are first-party integrations and controlled examples, not claims of
independent adoption or complete user-experience validation.

## Supporting projects

**[Bronto Pulse](https://github.com/Ponchia/bronto-pulse)** keeps private project-analytics history and evidence reports from GitHub, npm, Cloudflare and Search Console. It is a public source preview; live provider and operational validation remain separate from fixture tests.

**[Web Tooling](https://github.com/Ponchia/web-tooling)** provides reusable GitHub Actions checks for independent static websites. Each site retains its own deployment and credentials.

## Elsewhere

[Personal website](https://brontolotto.observer/) · [Ko-fi](https://ko-fi.com/ponchia)
