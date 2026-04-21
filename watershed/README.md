# Watershed — Clinician-Designed Wellness Support

A clinician-designed AI wellness companion built on the NASW Code of Ethics, unconditional positive regard, and the principle of the client as expert.

---

## Deploy to Vercel (recommended — free, 2 minutes)

1. Go to [github.com](https://github.com) and create a free account if you don't have one
2. Create a new repository called `watershed` and upload all these files
3. Go to [vercel.com](https://vercel.com) and sign up with your GitHub account
4. Click **Add New Project** → select your `watershed` repository
5. Leave all settings as default and click **Deploy**
6. Vercel will give you a live URL (e.g. `watershed.vercel.app`) — share that link

---

## Deploy to Netlify (alternative — also free)

1. Go to [netlify.com](https://netlify.com) and create a free account
2. Drag and drop this entire folder onto the Netlify dashboard
3. Netlify builds and deploys automatically — you get a shareable URL

---

## Run locally (for development)

```bash
npm install
npm run dev
```

Then open http://localhost:5173 in your browser.

---

## Important note on the API key

The prototype calls the Anthropic API directly from the browser. This is fine for internal testing and demos with trusted colleagues. Before any public launch, the API call should move to a backend server so the key is never exposed. Ask your developer to set up a simple Node/Express proxy endpoint for this.

---

## About

Watershed is a wellness support and psychoeducation tool. It is not a licensed clinical service. All clinical orientation, language standards, ethical frameworks, and knowledge bases are designed and maintained by licensed mental health clinicians. Watershed adheres to the NASW Code of Ethics and is grounded in unconditional positive regard and the principle of the client as expert.

Patent pending. Gabriel Ryan Kelley, sole inventor.
