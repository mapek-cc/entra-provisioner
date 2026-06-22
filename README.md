# Entra Provisioner — script generator

A self-contained, **offline** web UI that generates idempotent Entra ID (Azure AD)
provisioning scripts — **Bash** or **PowerShell**, both driving the `az` CLI.

**Everything runs client-side in your browser.** Nothing is uploaded anywhere and
nothing touches Azure during the interview. Review the generated script, then run it
yourself after `az login`.

👉 **Live:** https://mapek-cc.github.io/entra-provisioner/

- Generate app registration(s) (API + optional SPA), app roles, security groups,
  Microsoft Graph permissions, and a client secret.
- A **primary environment** (default `prod`) can drop the `-<env>` name suffix.
- UI in **English / Français / Español**, with a **light/dark** theme.

This page is the published copy of the generator UI; it is a single static HTML file
with no build step and no dependencies.
