# TechCrush Assignment React App

Simple React app with centered content:

`Dela built this for TechCrush`

## Run locally

1. Install dependencies:
   - `npm install`
2. Start dev server:
   - `npm run dev`

## Build

- `npm run build`

## Azure Web Apps deployment (GitHub Actions)

A custom workflow is included at:

- `.github/workflows/azure-webapp-deploy.yml`

Update these before deploying:

1. Set `AZURE_WEBAPP_NAME` in the workflow file.
2. Add GitHub repository secret:
   - `AZURE_WEBAPP_PUBLISH_PROFILE`
   - Value: publish profile downloaded from Azure Portal for your Web App.

After that, push to `main` to trigger deployment.
