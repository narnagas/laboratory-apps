# Deployment laboratory

Build-only YAML scaffold. GitHub PR validates the Angular build; main publishes the browser artifact. Future milestones promote the **same artifact** through IIS `dev.lalagunatech.com`, `stg.lalagunatech.com`, and `app.lalagunatech.com` with approvals. Agent, IIS paths, approvals and runtime metadata are not configured yet.

Docker belongs in `laboratory-apps-containers`.

Use Node.js 22 LTS and run `npm install`, `npm start`, or `npm run build`.
