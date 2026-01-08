---
description: Deploy all changes to GitHub Pages
---

# Deploy Portfolio Updates Workflow

This workflow ensures that every modification made to the portfolio is safely committed and pushed to the live site.

// turbo-all
1. Check git status to ensure all changes are tracked.
```powershell
git status
```

2. Add all modified files (html, css, images).
```powershell
git add .
```

3. Commit with a descriptive message.
```powershell
git commit -m "Auto-deploy: Update portfolio content and assets"
```

4. Push to the main branch to trigger GitHub Pages build.
```powershell
git push origin main
```

5. Verification: The site may take 30-60 seconds to reflect changes on GitHub Pages.
