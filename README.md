## 🎮 Using with Foundry VTT

### 1. Build and Install the Module

```bash
# Build the Foundry module
pnpm --filter @waystone/foundry-module build

# Package the module
cd apps/foundry-module
pnpm package

# Install in Foundry
# Copy waystone-bridge.zip to your Foundry Data/modules/ directory
# Or install via manifest URL (see docs/foundry-setup.md)
```

### 2. Link Foundry to Waystone

1. In Waystone web app, go to **Foundry → Link**
2. Select your campaign and click **Generate Link Code**
3. Copy the 6-character code
4. In Foundry VTT, click the Waystone icon (robot) in scene controls
5. Paste the link code and click **Link**
6. Verify connection status shows "Connected"

### 3. Start Playing

- AI DM controls all NPCs through Foundry
- Players act normally in Foundry
- Dice rolls execute transparently in Foundry
- Combat flows automatically with AI-controlled NPC turns

See [docs/foundry-setup.md](docs/foundry-setup.md) for detailed instructions.
# waystone-foundry-module
Foundry VTT module that connects to Waystone
