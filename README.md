<p align="right">
  <a href="https://brontolotto.observer/">Website ↗</a>&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/trevisanzeno/">LinkedIn ↗</a>
</p>

# Zeno Trevisan

Cloud architect and software engineer. I build open-source developer tools,
visual systems, and practical infrastructure software, usually starting with a
problem I keep running into.

## Find a tool for your project

The Bronto projects are independently usable tools, rather than a required
stack. Start with the problem you have and follow that project's own quickstart.

| What you need | Project | Try it or get started |
| --- | --- | --- |
| Catch responsive-layout regressions in alignment, spacing, and containment | **[Bronto Layout](https://github.com/Ponchia/bronto-layout)** — a local CLI and TypeScript library for approved layout contracts | [Reproduce a regression](https://github.com/Ponchia/bronto-layout/blob/main/docs/portfolio-regression-case-study.md) |
| Explain an existing chart, diagram, or interface with well-placed notes | **[Bronto Annotations](https://github.com/Ponchia/bronto-annotations)** — headless placement, connectors, and optional adapters | [Placement playground](https://ponchia.github.io/bronto-annotations/#playground) · [Editing example](https://ponchia.github.io/bronto-annotations/examples/react-incremental/) |
| Build a dashboard, tool panel, or report with normal HTML | **[Bronto UI](https://github.com/Ponchia/bronto-ui)** — CSS-first building blocks, tokens, and optional JavaScript behaviors | [One-file example](https://ponchia.github.io/bronto-ui/demo/first-steps.html) · [Compositions](https://ponchia.github.io/bronto-ui/examples/) |
| Embed editable diagrams and charts with previewable, guarded changes | **[Bronto Visual Models](https://github.com/Ponchia/bronto-visual-models)** — identified visual content with edit previews, replay, and undo | [Interactive demo](https://ponchia.github.io/bronto-visual-models/) · [First model](https://github.com/Ponchia/bronto-visual-models/blob/main/docs/getting-started.md) |
| Keep a private, source-aware history of software and website activity | **[Bronto Pulse](https://github.com/Ponchia/bronto-pulse)** — analytics collection and evidence reports from existing sources | [Run the synthetic demo](https://github.com/Ponchia/bronto-pulse#run-the-complete-demo) · [Validation boundaries](https://github.com/Ponchia/bronto-pulse/blob/main/docs/validation.md) |

UI and Annotations publish pre-1.0 releases; Layout and Visual Models are betas.
Pulse is a public source preview with npm betas. Each repository documents its
supported environments, current package, and limitations. Source documentation
can be ahead of the published package.

## Infrastructure

**[Vaultwarden ESO Provider](https://github.com/Ponchia/vaultwarden-eso-provider)**
connects selected vault items to Kubernetes through External Secrets Operator.
The current release qualification is Vaultwarden-only; Bitwarden Cloud remains
unverified. Start with the [release status](https://github.com/Ponchia/vaultwarden-eso-provider#release-status)
and [compatibility matrix](https://github.com/Ponchia/vaultwarden-eso-provider/blob/main/docs/compatibility.md).

**[Web Tooling](https://github.com/Ponchia/web-tooling)** provides reusable GitHub
Actions checks for independent static websites. Each site owns its deployment
and credentials.

## Browser experiments

**[Sense6](https://sense6.net/en/)** explores perception and response timing,
with a private local journal. Results describe a task on a particular device;
they are not medical measurements. [Source and methods](https://github.com/Ponchia/sense6).

## Evidence and contributions

[Bronto in practice](docs/bronto-in-practice.md) documents a real UI/Layout CI
integration and a separate installed-package Visual Models example. These are
first-party examples, not claims of independent adoption.

Reproducible bug reports, integration feedback, and focused contributions are
welcome in the relevant repository. Its contributing and security guides explain
where to start and how to report vulnerabilities privately.

---

[Personal website](https://brontolotto.observer/) ·
[LinkedIn](https://www.linkedin.com/in/trevisanzeno/) ·
[Support maintenance on Ko-fi](https://ko-fi.com/ponchia)
