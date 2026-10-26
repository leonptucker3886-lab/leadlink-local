# LeadLink Local
Pay-per-sale lead tracker for local video ads (single `index.html`, Supabase backend via RPC).

Routes (hash-based): `#/` admin dashboard (admin key), `#/ad/<slug>?src=tiktok-video1` customer offer + code, `#/c/<key>` customer purchase confirm, `#/o/<key>` business owner portal, `#/inv/<slug>` printable invoice, `#/pitch` pitch kit + referral agreement template.

Requires the `ll_*` RPC functions in the Supabase project referenced in `index.html`. Static site, deploys on Vercel with no build step.
