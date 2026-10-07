# Design Skill

A personal design skill for creating and reviewing polished interfaces. It combines motion and component guidance adapted from [Emil Kowalski's Skills for Designers and Engineers](https://github.com/emilkowalski/skills) with added guidance for expressive layouts, mobile screens, subscription paywalls, and Sanzo Wada color combinations.

## What's inside

- [SKILL.md](SKILL.md): design and motion guidance, including three-plane composition, one action color, scale contrast, and clear subscription offers.
- [Visual examples](references/visual-examples.md): written descriptions of layered product, music, and weather screens. The original reference screenshots are not distributed here.
- [Sanzo Wada color guide](references/sanzo-wada-colors.md) and [palette catalog](references/sanzo-wada-palettes.json): 348 numbered combinations with approximate digital colors.

## Use with Codex

Clone this repository into your personal skills directory:

```sh
git clone https://github.com/KELVI23/Design-skill.git ~/.codex/skills/design
```

Then ask Codex to use the `design` skill when building or reviewing an interface. For another agent that supports `SKILL.md`, place this repository in that agent's skills directory.

This skill is distributed directly from GitHub.

## Attribution and licenses

The motion and component material is adapted from [Emil Kowalski's `emil-design-eng` skill](https://github.com/emilkowalski/skills/tree/main/skills/emil-design-eng). Emil's MIT license and copyright notice are retained in [LICENSE](LICENSE).

The palette catalog is derived from [Matt DesLauriers's corrected Sanzo Wada dataset](https://github.com/mattdesl/dictionary-of-colour-combinations); its MIT notice is retained in [references/sanzo-wada-data-LICENSE.md](references/sanzo-wada-data-LICENSE.md). The combinations originate with Sanzo Wada's *A Dictionary of Color Combinations*. The [interactive dictionary](https://sanzo-wada.dmbk.io/) is a useful visual companion. Digital hex values approximate printed colors, so verify contrast in your interface.
