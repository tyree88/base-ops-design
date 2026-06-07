# Base — Operating System (public site)

Static deploy of the Base operational-systems-design take-home presentation.
**Deploy-only mirror** — published to Vercel; the design reasoning lives in a private working repo.

Tabs: **Walkthrough** (scrollytelling showcase) · **Framework** (decision hub) · **Brain** (knowledge graph).

`public/` is the web root (`vercel.json` → `outputDirectory: public`). Self-contained static HTML; no build step.
Regenerated from the working repo via its `sync-public.sh` + `publish-site.sh`.
