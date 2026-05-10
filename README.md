# vfg-portal

Three static HTML compliance portals (CCO, Investment Advisor, Insurance) deployed via GitHub Pages at `voltafinancial.github.io/vfg-portal/`. Each portal hits the unified **volta-crm** Supabase project (`umypmthtniofwaddjhpz`) directly through PostgREST + Supabase Auth, gated by RLS — see `volta-crm/supabase/migrations/0050–0055` for the schema and policy port.
