# Bronto in practice: build, explain and verify

Bronto is a set of separately usable tools, not a framework that requires every
package. The examples below show concrete boundaries and reproducible checks.
They use projects maintained by the same author. They are not independent-user
acceptance, a security audit or evidence of broad adoption.

## A real downstream CI integration: UI + Layout

[Bronto UI](https://github.com/Ponchia/bronto-ui) builds the interface and static
website. [Bronto Layout](https://github.com/Ponchia/bronto-layout) checks the
website's approved responsive geometry. The website, not the checking tool,
owns the selectors and design relationships in
[its contract directory](https://github.com/Ponchia/bronto-ui/tree/main/test/layout).

A developer can follow that directory's README and the
[complete downstream case study](https://github.com/Ponchia/bronto-layout/blob/main/docs/real-consumer-brontoui.md)
to inspect the exact workflow, generated pages and controlled failures.
The workflow builds the candidate source, serves the output locally and pins
Layout to a reviewed source revision. It does not inspect private browsing data.

The recorded initial integration checked the homepage, operations-page shell
and directly navigated service dashboard: 159 approved rule/viewport evaluations.
It also required two intentionally introduced failures: a 3px horizontal overflow
and an 8px toolbar/panel misalignment. The latter was caught by its approved
relationship even though a generic audit reported no measured errors.

Those figures describe the historical integration evidence linked above, not a
new measurement of today's website. A later first-party beta upgrade added an
interior-width probe that caught a controlled defect between passing endpoints.
A passing contract still does not prove untested widths, iframe interior sizing,
paint order, screen-reader behavior or overall visual quality. The browser tests
and human review remain separate checks.

## An installed-package example: Visual Models

[The first-model walkthrough](https://github.com/Ponchia/bronto-visual-models/blob/main/docs/getting-started.md)
starts with an actual GitHub Release archive and an empty directory. Its
[executable example](https://github.com/Ponchia/bronto-visual-models/blob/main/examples/first-model.mjs)
creates an identified graph, previews a guarded edit without writing, commits
it, replays the same operation key, refuses a stale edit and undoes the rename.
Every result is asserted. No React, visualization engines, account or Spatial
server is needed for that headless path.

The same example runs in a clean packed consumer in CI; the published archive
has a separate public download, tag and checksum check. The
[interactive demo](https://ponchia.github.io/bronto-visual-models/) adds optional
views. Production hosts must still supply durable storage and authorization;
the in-memory example is not a deployment or collaborative-storage recipe.

## Where Annotations fits

[Bronto Annotations](https://github.com/Ponchia/bronto-annotations) places notes
and connectors around geometry supplied by a chart, diagram or other host.
It does not replace the charting engine, own persistence or require Visual
Models. Its [SVG example](https://ponchia.github.io/bronto-annotations/examples/svg-basic/)
shows that smaller integration boundary. Start with one tool and add another
only when the application actually needs its responsibility.

[Back to the portfolio](../README.md)
