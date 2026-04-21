# Portfolio Website Deployment Plan - Kolunya Zone

## Goal
Build and deploy a modern, dark-themed UX/UI designer portfolio on GitHub Pages.

## Specs
1. **Theme:** Modern dark theme.
2. **Typography:** JetBrains Mono font.
3. **Hero:** "Kolunya Zone" (UX/UI Designer).
4. **Projects:** 3 distinct project showcases.
5. **Contact:** Clear contact details section.

## Implementation Steps

### Phase 1: Local Development
1. **Initialization:**
   - Create directory `portfolio`.
   - Create `index.html`, `style.css`, and `script.js`.
2. **Structure:**
   - Implement semantic HTML: Header, Hero, Projects (3 cards), and Contact.
3. **Styling:**
   - Implement dark theme (deep grays/blacks).
   - Integrate JetBrains Mono via Google Fonts.
   - Apply responsive design using CSS Grid/Flexbox.

### Phase 2: Version Control
1. Initialize git: `git init`.
2. Commit files: `git add . && git commit -m "feat: initial portfolio structure"`.
3. Push to GitHub repository.

### Phase 3: Deployment
1. Navigate to GitHub Repo > Settings > Pages.
2. Set source to "Deploy from a branch" -> `main` -> `/(root)`.
3. Save and wait for deployment.
