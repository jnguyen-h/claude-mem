# GKE Tenant Onboarding Guide

A self-contained, static onboarding tutorial for tenant teams bringing an
application or service onto the shared GKE platform.

## Usage

Open `index.html` directly in a browser, or serve the folder with any
static file host (it has no build step and no external dependencies beyond
Google Fonts). Per-viewer checklist progress is stored in `localStorage`.

## Editing

The example values throughout (project ID, cluster name, tenant slug,
Slack channels, Artifact Registry paths, etc.) are illustrative — swap them
for your platform's real names before handing this to tenants. Content
lives entirely in `index.html`; there is no templating layer.
