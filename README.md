# CHAMPS — Caring Has No Distance

CHAMPS is a mobile-first community application for senior citizens, families and volunteers.

## Included in this version
- Multi-step onboarding and role selection
- Home dashboard and CHAMPS journey
- Support request creation and status tracking
- Volunteer discovery and community connections
- Persistent local messaging demo
- Activities, programs and RSVP tracking
- Profile, emergency contact and privacy/safety section
- Accessibility: large text, high contrast and reduced motion
- Notification center
- Responsive mobile-first UI and PWA manifest
- Local persistence with browser storage; no paid backend required for the demo

## Run

```bash
npm install
npm run dev
```

For a production build:

```bash
npm run build
npm run preview
```

## Next production step
Connect the existing data model to Supabase (or another backend) for authentication, secure profiles, real volunteer matching, messages, notifications and role-based access. The UI is intentionally usable without a backend first.
