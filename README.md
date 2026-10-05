# My Little Calm

A free, private coping app for teens (13-18) with a parent/guardian info page.
Short exercises (slow breathing, naming feelings, 5-4-3-2-1 grounding, cloud pop)
earn resources that grow a little 3D island with a character named Pip.

It is a practice space, **not therapy**, and it does not claim to solve teen
mental health challenges.

## Stack
Static site: one `index.html` (HTML, CSS, JS). No build step.
Three.js r128 loads from cdnjs. Progress is saved in the browser's localStorage.
Nothing a user types is sent anywhere.

## Run locally
```
npm run dev
```
or open `index.html` in a browser.

## Deploy to Vercel
**Dashboard:** push this folder to GitHub, then Vercel > Add New > Project > import the repo.
Framework Preset: **Other**. Build Command: leave empty. Output Directory: leave empty (root).

**CLI:**
```
npm i -g vercel
vercel        # preview
vercel --prod # production
```

## Notes
- Crisis numbers are US-only (988, text HOME to 741741, 911). Add local lines for other countries.
- Chat replies are simple keyword rules, not AI.
- Origin: mechanics ported from the "My Little Universe" Unity prototype (resource collection, area unlocking, save/load) plus the "Mind Island" prototype.
