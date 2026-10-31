# Fakher Task Desk

Shared tasks with deadlines, completion tracking, and member attribution.

## Hosting
Serve index.html and supabase.js together as static files. GitHub Pages deployment is pending owner approval for public repository visibility.

## Authentication
Passwordless email magic-link sign-in uses the existing Fakher Tasks Supabase project. Before use, configure Supabase Auth Site URL and redirect allowlist to the deployed application URL. Each staff email must be approved in the existing allowed_emails table. Membership and task access are enforced by database RLS. Do not disable RLS or expose service-role keys.

The bundled Supabase JS library is pinned to 2.95.3. Browser notifications require the application to remain open. Email-to-task import is manual.

## Status
Source uploaded; GitHub Pages and passwordless redirect configuration are not yet activated. The previous ChatGPT-hosted deployment is separate.
