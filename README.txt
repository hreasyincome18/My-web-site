NOVA X website package

Files:
- index.html: user-facing website
- admin.html: separate admin panel

Storage configuration expected:
- Supabase bucket site-images: Public
- Supabase bucket user-uploads: Private
- Firebase project: ar-income-live
- Supabase Firebase Third-Party Auth must be enabled for project ar-income-live

Important:
These are the latest prepared source files containing Firebase-token-based Supabase upload/signing code. They have not been live-tested against your Supabase project or deployed on Netlify. Do not delete Firebase rules or make Storage write access public. If upload fails, share the exact error before changing policies.

Netlify:
Upload the ZIP as a site deploy only after confirming these are the intended latest files. Keep index.html and admin.html at the ZIP root.
