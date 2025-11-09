# UI & Authentication Enhancement Spec

## Goals
- Modernize the UI using Tailwind CSS with a professional, clean look
- Use pastel color palette for backgrounds, buttons, and icons (no high gradients)
- Icons: pastel fill, darker pastel outline
- Refactor all templates for consistent, accessible, and responsive design
- Add a basic authentication system (username/password, session-based, no JWT)
- Add login/logout UI and logic
- Restrict access to main pages unless logged in
- Show user info and logout in header when logged in
- Update README with new setup/auth instructions

- [x] Integrate Tailwind CSS (CDN already in base.html)
- [ ] Define pastel color palette and icon style *(see below)*
- [x] Refactor `base.html` for new layout, header, and nav
- [x] Refactor all templates for new UI
- [x] Add login page and route
- [x] Add logout route
- [x] Add user model and authentication logic
- [x] Restrict access to main pages
- [x] Show user info/logout in header
- [ ] Update README for new auth system

### Pastel Palette & Icon Style
- Use Tailwind's `bg-pastel-*` custom classes for backgrounds (to be defined in templates)
- Use light pastel fills for icons, with a darker pastel outline (SVG inline or Heroicons outline/solid with custom color)
