# Koozee for Antigravity

Create fashion images and videos with AI—all in one place.

Koozee is an AI visual marketing tool for fashion retailers, brands, and entrepreneurs. Use it with Antigravity to create virtual try-ons, on-model lifestyle images, and fashion marketing videos with simple prompts. Let Antigravity run workflows to generate images and videos in batches, or build your own on Koozee’s visual canvas. From product listings to marketing campaigns, create compelling visuals and make your products stand out.

This repository is an Antigravity plugin for 2.0, IDE, and CLI. The clone root has `plugin.json` and `mcp_config.json`.

- Product: [koozee.ai](https://koozee.ai)
- MCP: `https://koozee.ai/business-api/mcp` (`serverUrl`)
- License: MIT

## Install

Clone this repository. The clone root is the plugin root.

```bash
git clone https://github.com/Koozee-Studio/koozee-antigravity.git
cd koozee-antigravity
agy plugin install .
```

Antigravity 2.0 / IDE: put this folder in the workspace `.agents/plugins/` or the global `~/.gemini/config/plugins/`.

The first MCP connection uses OAuth. Calls without login return 401.

Credits match the Koozee canvas. After the canvas changes, open the project URL Koozee returns.

## Support

- Website: https://koozee.ai
- Contact: https://koozee.ai/contact-us
