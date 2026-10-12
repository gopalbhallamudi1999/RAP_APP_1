# RAP Fiori UI app (BSP deployment)

Replace placeholders before deploying:
- manifest.json: <zui_service_binding>, <zui_service_definition>, <EntitySet>
- ui5.yaml / ui5-deploy.yaml: <YOUR-ABAP-SYSTEM-HOST>, client, BSP name, package, transport

Steps:
1. npm install
2. npm start            (local preview)
3. npm run deploy       (builds and deploys to ABAP BSP repository)

Manual alternative: npm run build, zip the contents of dist/, upload via
report /UI5/UI5_REPOSITORY_LOAD in SE38.
