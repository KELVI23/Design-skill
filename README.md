# Design Skill

A personal collection of 13 design and engineering skills based on [Emil Kowalski's Skills for Designers and Engineers](https://github.com/emilkowalski/skills). The main `design` skill retains Emil's design engineering guidance and adds expressive layouts, mobile screens, subscription paywalls, and Sanzo Wada color combinations. The other 12 skills are included in [skills](skills).

## What's inside

- [SKILL.md](SKILL.md): design and motion guidance, including three-plane composition, one action color, scale contrast, and clear subscription offers.
- [Visual examples](references/visual-examples.md): written descriptions of layered product, music, and weather screens. The original reference screenshots are not distributed here.
- [Sanzo Wada color guide](references/sanzo-wada-colors.md) and [palette catalog](references/sanzo-wada-palettes.json): 348 numbered combinations with approximate digital colors.

### Companion skills

- [animate](skills/animate/SKILL.md) and [animate-expo](skills/animate-expo/SKILL.md): build motion for web and native interfaces.
- [review-animations](skills/review-animations/SKILL.md), [improve-animations](skills/improve-animations/SKILL.md), and [find-animation-opportunities](skills/find-animation-opportunities/SKILL.md): review motion, plan improvements, and decide where it helps.
- [animation-vocabulary](skills/animation-vocabulary/SKILL.md): describe motion precisely.
- [apple-design](skills/apple-design/SKILL.md), [mobile-native](skills/mobile-native/SKILL.md), and [write-swift](skills/write-swift/SKILL.md): interface and native app guidance.
- [pick-ui-library](skills/pick-ui-library/SKILL.md), [prototype](skills/prototype/SKILL.md), and [ask-sonner](skills/ask-sonner/SKILL.md): choose components, explore variants, and work with Sonner.

## Use with Codex

Clone this repository into your personal skills directory:

```sh
git clone https://github.com/KELVI23/Design-skill.git ~/.codex/skills/design
```

This activates the main `design` skill. To activate Emil's 12 companion skills as separate skills too:

```sh
cp -R ~/.codex/skills/design/skills/* ~/.codex/skills/
```

Then ask Codex to use the skill that fits your task. For another agent that supports `SKILL.md`, place the main skill and companion folders in that agent's skills directory.

This skill is distributed directly from GitHub.

## Attribution and licenses

The main skill adapts [Emil Kowalski's `emil-design-eng` skill](https://github.com/emilkowalski/skills/tree/main/skills/emil-design-eng). The 12 companion skills are copied from Emil's collection. His MIT license and copyright notice are retained in [LICENSE](LICENSE).

The palette catalog is derived from [Matt DesLauriers's corrected Sanzo Wada dataset](https://github.com/mattdesl/dictionary-of-colour-combinations); its MIT notice is retained in [references/sanzo-wada-data-LICENSE.md](references/sanzo-wada-data-LICENSE.md). The combinations originate with Sanzo Wada's *A Dictionary of Color Combinations*. The [interactive dictionary](https://sanzo-wada.dmbk.io/) is a useful visual companion. Digital hex values approximate printed colors, so verify contrast in your interface.
