# plugin-locale-en

English language for [Cuelith](https://github.com/Cuelith/cuelith-core). In Cuelith languages are modules too: this is a data-only module (`runtime: none`, no process), shipped with the core next to Italian. The language is chosen in Settings → General.

- `cuelith-plugin.json` — manifest (family `locale`).
- `locales/en.json` — flat catalogue `key → text`. Placeholders `{name}`; plurals with the `#one` / `#other` suffixes.

Every key used by the core (`core.*`) and the protocol (`protocol.*`) must have its translation here, with the same placeholders as the Italian catalogue in `plugin-locale-it`: the language test in `cuelith-core` fails if one is missing.

Apache 2.0 licence.
