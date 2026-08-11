# Palevie — Landing Page

Static landing page for Palevie, a Korean personal-color beauty service.

## Structure
- `index.html` — the entire page (HTML + CSS + JS in one file)
- `assets/` — WebP images (hero, step cards, product flatlay, season cards, silk band)

## Deploying
Any static host works. For GitHub Pages: Settings → Pages → deploy from the branch
root, and the site serves `index.html` directly.

## Before launch
- **The waitlist form does not store emails yet.** It only shows a thank-you message.
  Connect it to a real endpoint (Formspree, Buttondown, or a Supabase table) so
  signups are actually captured.
- Fill in real links for `/privacy` and `/terms` in the footer.
- Replace `hero.webp` if you generate a cleaner version — the current crop comes from
  a mockup that had faint vertical divider lines baked into it.

## Notes on claims
Press logos, signup counts, and testimonials were deliberately left out. Adding
unearned press badges or invented review counts would be deceptive advertising under
FTC rules, and magazine logos carry trademark risk. The layout keeps room for these —
add them once they are real.
