<p align="center">
  <a href="https://agiexa.com"><img src="assets/logo.png" alt="Agiexa" width="140" height="140"></a>
</p>

# Agiexa ClawHub skills

Preview skills for OpenClaw, published on [ClawHub](https://clawhub.ai). Each one explains what Agiexa will do for an integration (tools, triggers, use cases, how it works), links to its page on agiexa.com, and - only with the user's explicit permission - adds them to the launch waitlist via `POST https://agiexa.com/api/agent/waitlist`.

| Slug | Display name |
| --- | --- |
| `agiexa-shopify` | Shopify Store Management via Agiexa |
| `agiexa-gmail` | Gmail for Shopify via Agiexa |
| `agiexa-klaviyo` | Klaviyo for Shopify via Agiexa |
| `agiexa-google-analytics` | Google Analytics for Shopify via Agiexa |
| `agiexa-smile-io` | Smile.io for Shopify via Agiexa |
| `agiexa-gorgias` | Gorgias for Shopify via Agiexa |
| `agiexa-judge-me` | Judge.me for Shopify via Agiexa |
| `agiexa-printify` | Printify for Shopify via Agiexa |
| `agiexa-shipengine` | ShipEngine for Shopify via Agiexa |
| `agiexa-zendesk` | Zendesk for Shopify via Agiexa |

## Build

`skills/` is generated - do not edit it by hand. Content comes from the marketing site (`../agiexa-site/src/data/integrations/*.json` and `launchMonth` in `src/config/site.ts`); templates live in `scripts/build.mjs`.

```bash
node scripts/build.mjs                       # expects ../agiexa-site
AGIEXA_SITE_DIR=/path/to/agiexa-site node scripts/build.mjs
```

Adding a skill: add an entry to `SKILLS` in `scripts/build.mjs` **and** its slug to the allowlist in `agiexa-site/src/app/api/agent/waitlist/route.ts`, then deploy the site before publishing the skill.

## Publish

```bash
clawhub login
clawhub skill publish skills/agiexa-shopify --slug agiexa-shopify --name "Shopify Store Management via Agiexa" --version 1.0.0
clawhub skill publish skills/agiexa-gmail --slug agiexa-gmail --name "Gmail for Shopify via Agiexa" --version 1.0.0
# ...same pattern for the rest of the table above
```

Bump `VERSION` in `scripts/build.mjs`, rebuild, and pass the new `--version` (plus `--changelog`) when updating.
