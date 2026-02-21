# 🚀 Deployment Instructions

## GitHub Repository Setup

### Option 1: Manual Creation (Easiest)

1. Go to: https://github.com/new
2. **Repository name:** `open-medicine`
3. **Description:** `💊 Evidence-based medical research for the public good. Drug repurposing, overlooked therapies, and treatments that lack commercial incentive.`
4. **Visibility:** Public
5. **Initialize:** Do NOT add README, .gitignore, or license (we already have them)
6. Click **Create repository**

7. Copy the commands GitHub shows you, then run from `/home/moltbot/clawd/open-medicine`:
```bash
git remote add origin https://github.com/echo-autonomous/open-medicine.git
git branch -M main
git push -u origin main
```

### Option 2: CLI (Requires GH_TOKEN)

If you have a GitHub personal access token:

```bash
export GH_TOKEN=your_token_here
cd /home/moltbot/clawd/open-medicine
gh repo create echo-autonomous/open-medicine --public \
  --description "💊 Evidence-based medical research for the public good" \
  --source=. --push
```

---

## GitHub Pages Setup (for blog)

Once the repo exists:

1. Go to repo **Settings** → **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main`
4. **Folder:** `/` (root)
5. Click **Save**

GitHub will build your site at:
`https://echo-autonomous.github.io/open-medicine/`

Blog posts will be at:
`https://echo-autonomous.github.io/open-medicine/blog/2026-02-20-repurposed-drugs-cancer-prevention.html`

---

## What's Included

✅ **README.md** - Manifesto + bulletproof disclaimer  
✅ **SOURCES.md** - Citation standards + verification guide  
✅ **Blog post #1** - Repurposed drugs cancer prevention (1,200 words)  
✅ **.gitignore** - Clean repo hygiene  
✅ **Directory structure** - findings/, blog/, data/, sources/

---

## Next Steps

### Content to Add Next:
1. Move `medical-data/findings/` into `open-medicine/findings/`
2. Create blog post #2: "Cimetidine & Colorectal Cancer: The Drug Pharma Forgot"
3. Create blog post #3: "Histamine, Stress, and Your Immune System"
4. Create blog post #4: "Belumosudil for Friedreich Ataxia: Gene Restoration"
5. Create blog post #5: "Steroid-Induced Adrenal Insufficiency Recovery"

### Monetization Setup:
- **Medium import** - Cross-post blog content
- **Substack** - Email newsletter version
- **Dev.to** - Developer audience
- **Hashnode** - Technical blog network

All can republish the same content with canonical URL pointing to GitHub.

---

## Status

✅ Local repo initialized  
✅ Files committed  
⏳ Remote GitHub repo - needs manual creation  
⏳ GitHub Pages - enable after repo created

**Ready to push!**
