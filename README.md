# Bikeep partner plugins

Public marketplace for Bikeep's sales partners.

| Plugin | What it does |
|---|---|
| `bikeep-partner-tools` | One skill that tells Claude how to build Bikeep proposals with the Bikeep connector (`https://partners.bikeep.com/api/mcp`). Prices, terms, product facts, brand assets and the document recipe all come from the connector, so nothing in this repo needs updating when prices change. |

## Install

- **claude.ai (Pro/Max):** add the Bikeep connector from the link in your welcome email, then add this marketplace and install `bikeep-partner-tools`.
- **Team/Enterprise:** your Claude Owner adds the connector and provisions the skill zip from the latest release.
- **Claude Code:** `/plugin marketplace add Bikeep-Inc/bikeep-partner-plugins`, then `/plugin install bikeep-partner-tools@bikeep-partner-plugins`.

This repo contains no prices, contacts or internal information, by design. CI rejects hooks, agents, binaries, any change to the connector URL, and any price, email or phone number in a skill.
