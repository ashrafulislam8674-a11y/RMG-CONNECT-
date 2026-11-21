# RMG Connect — starter prototype

This is a responsive front-end prototype for a bilingual (Bangla + English) RMG job portal.

## Run
Open `index.html` in a modern browser. No build step is required.

## Included in this prototype
- Home page and job category cards
- Job search and category filtering
- Sample RMG job listings
- Demo admin page to publish/delete posts
- Bangla/English interface toggle
- Browser-local persistence using localStorage

## Important limitations
This is a front-end demo, not a production job portal. It has no real admin authentication, cloud database, applicant accounts, application tracking, push notifications, or Android APK. The demo admin page is intentionally not secure and must not be exposed as a real admin system.

## Recommended production architecture
- Website: Next.js or React
- Android: Flutter (or package the responsive web app as a PWA first)
- Backend/database: Firebase Authentication + Firestore
- File storage: Firebase Storage
- Notifications: Firebase Cloud Messaging
- Hosting: Firebase Hosting or Vercel

## Before public launch
1. Create secure admin roles and server-side authorization.
2. Move job posts and applications into a cloud database.
3. Add employer verification, report/flag tools, and moderation.
4. Add privacy policy, terms, and contact details.
5. Test Bangla fonts, accessibility, and mobile layouts.
6. Build and test the Android app before publishing.
