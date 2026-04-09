# Contributing to M2C2 Library

## Adding Your Addon

### Option 1 — Official Library (Recommended)
1. Fork this repo
2. Create a folder in addons/ named your addon id
   Example: addons/my-cool-widget/
3. Add all required files (see addon spec below)
4. Submit a Pull Request
5. We review and merge — your addon is live for all M2C2 users

### Option 2 — Community Listing
Keep your addon in your own GitHub repo and submit 
just your manifest.json to TorNation01/m2c2-marketplace
via Pull Request to be listed in the marketplace.

## Required Files
- manifest.json (see spec)
- README.md
- thumbnail.png (400x300px)
- widget/[YourAddon]Widget.tsx

## Addon Spec
See the full developer guide at docs.anakatech.com/m2c2/addons

## Review Criteria
- No malicious code
- Valid manifest.json
- Working widget component
- Clear README with setup instructions
- Open source license
