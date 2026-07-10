@"
# TapCard

NFC-enabled digital business card platform. Tap to share your profile instantly.

## Status
Static HTML prototype — landing page, order flow, and admin dashboard.
Backend (Supabase) and payment integration (Stripe) planned.
"@ | Out-File -FilePath README.md -Encoding utf8

git add .
git commit -m "Add README"
git push
