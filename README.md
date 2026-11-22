# iYojana CRM preview — development branch

This branch preserves the existing standalone `index.html` preview on the default branch and adds an experimental React/Vite prototype under `src/`.

## Run React prototype
```bash
npm install
npm run dev
```
Open the Vite URL shown in the terminal. The original `index.html` remains intact and may load the original standalone preview rather than the new React entrypoint. To test the React version, use a separate HTML entry file or migrate the entrypoint deliberately after reviewing the original.

## Prototype modules
Dashboard, leads, clients, activities, KYC, financial goals, revenue, employees, business targets and document-import placeholder.

## Important limitations
The React prototype uses browser localStorage and synthetic data. No backend, authentication, roles, shared database, real KYC verification or document extraction is implemented. Do not enter real client data. Twenty CRM is not yet integrated. No build or end-to-end test has been verified.

## Next steps
Review original index.html and exported Google AI Studio code, choose which UI to preserve, wire a backend and access controls, test workflows, then prepare a shareable deployment.
