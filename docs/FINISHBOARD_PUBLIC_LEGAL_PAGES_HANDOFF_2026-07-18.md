# FinishBoard public legal pages handoff — 2026-07-18

## Canonical repo evidence

- Repo: `/Users/jerryng/Desktop/Jerry IOS Project/WarrantyProof-Privacy-Site`
- Remote: `https://github.com/jerryng145/warrantyproof-privacy-policy.git`
- Branch at inspection: `main`
- Starting HEAD: `5a163ae3b35345125a01347242eb4ec69315ecb6`
- Starting worktree: clean
- Framework/build: static HTML/CSS GitHub Pages site; no package manager or JS build is required.
- Existing routes: root pages such as `privacy.html`, `support.html`, `terms.html`, and app/category pages linked by relative HTML navigation.
- Existing app-page audit: WarrantyProof has existing Support, Privacy, Terms, home, and category pages. No second independent E STREAM MEDIA app website page was found in this repo; no stronger canonical website repo was found within the inspected Desktop scope.

## FinishBoard public routes

- `finishboard/support/index.html` → proposed `https://www.estreamedia.my/finishboard/support`
- `finishboard/privacy/index.html` → proposed `https://www.estreamedia.my/finishboard/privacy`
- `finishboard/terms/index.html` → proposed `https://www.estreamedia.my/finishboard/terms`
- `finishboard/index.html` → proposed `https://www.estreamedia.my/finishboard/`

The pages reuse the existing static-site approach: responsive viewport, system font stack, light card layout, relative navigation, title/description metadata, and canonical links. The FinishBoard page set is additive and does not modify existing WarrantyProof claims or routes.

## 2026-07-19 public-page update

- Publisher identity is now set to `E STREAM MEDIA`.
- Support contact is now `admin@estreamedia.my`.
- The FinishBoard page copy now uses production-facing public page language.
- Terms copy now allows for premium plans or in-app purchases to be processed by the app store when offered.
- Static local validation should be rerun before any push/deployment, followed by HTTPS readback of all target URLs.

## 2026-07-19 deployment readback

- GitHub Pages source deployment is public and returns HTTP 200 for:
  - `https://jerryng145.github.io/warrantyproof-privacy-policy/finishboard/`
  - `https://jerryng145.github.io/warrantyproof-privacy-policy/finishboard/support/`
  - `https://jerryng145.github.io/warrantyproof-privacy-policy/finishboard/privacy/`
  - `https://jerryng145.github.io/warrantyproof-privacy-policy/finishboard/terms/`
- Each GitHub Pages URL read back `FinishBoard`, `E STREAM MEDIA`, and `admin@estreamedia.my`.
- The requested canonical `www.estreamedia.my/finishboard/...` URLs currently return 404 and redirect to `/en/finishboard...`; do not mark the target-domain legal URL gate as PASS until the domain mapping is fixed or a different App Store URL is explicitly chosen.

No DNS change, hosting-console action, ASC mutation, App Store submission, or app release action is recorded in this page report.
