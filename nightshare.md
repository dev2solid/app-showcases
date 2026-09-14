# NightShare

A shared photo and video album for real-world events. Guests open one event link, contribute media, and browse the collected memories without installing an app.

## Product workflow

An event starts with easy contributions, then moves into album-focused Memories Mode. Guests can add from their gallery, share the album, filter photos and videos, and open individual originals from a full-screen viewer.

## Engineering decisions

The development record describes a React/Vite PWA with Supabase media metadata and object storage. Optimistic upload previews give the uploader immediate feedback; event-scoped realtime subscriptions and fallback polling update other viewers. A later viewer revision mounts one media item at a time and uses native video controls for original files.

## Scope and evidence

The supplied development conversation records deployment and actual event use. It does not establish a production-ready multi-tenant platform. Host accounts, planner dashboards, payments, and multi-event administration were discussed as future work and are not claimed as delivered here. Current backend permissions and live deployment behavior have not been independently audited for this showcase.

## Public showcase boundary

Use fictional event names and original generic artwork. Exclude guest photos, videos, personal names, event URLs, backend project identifiers, credentials, exports, and deployment configuration. Do not connect a portfolio demo to the original event backend.
