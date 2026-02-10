# SuperPlane Render Test Service

This is a minimal static site for testing the SuperPlane Render integration.

## What's included

- Simple HTML page with gradient background
- `render.yaml` blueprint for easy Render deployment
- Environment variable example

## Deploy to Render

1. Go to https://dashboard.render.com
2. Click **New** → **Blueprint**
3. Connect this repository
4. Deploy!

## Testing SuperPlane Components

Once deployed, you can test these components in SuperPlane:

- ✅ **Get Service** - Fetch service details
- ✅ **Deploy** - Trigger a new deploy
- ✅ **Get Deploy** - Get deploy status
- ✅ **Cancel Deploy** - Cancel an active deploy
- ✅ **Rollback Deploy** - Rollback to previous version
- ✅ **Purge Cache** - Clear build cache
- ✅ **Update Env Var** - Modify TEST_ENV_VAR

## API Key

Use your Render API key (starts with `rnd_`) in SuperPlane's Render integration configuration.
