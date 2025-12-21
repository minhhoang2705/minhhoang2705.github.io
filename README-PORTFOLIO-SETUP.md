# Portfolio Setup Status - Tran Hoang Minh

**Last Updated**: 2025-12-21
**Status**: ✅ Configuration Complete | ⏳ Content Population in Progress

---

## ✅ What's Done

### Configuration & Setup (100% Complete)
- ✅ Blog/news system disabled
- ✅ Collections cleaned (removed books, news)
- ✅ Config marked with TODO comments
- ✅ Example content excluded
- ✅ Jekyll archives disabled
- ✅ RSS feed disabled (no blog)

### Resume & CV (100% Complete)
- ✅ `assets/json/resume.json` - Complete CV in JSON Resume format
- ✅ All sections populated from your CV
- ✅ Old `_data/cv.yml` deleted
- ✅ Your CV page is ready to display

### Social Media (100% Complete)
- ✅ Email: minhhtran.work@gmail.com
- ✅ GitHub: minhhoang2705
- ✅ LinkedIn: tranhminh8464
- ✅ Icons will display on About page

### Templates Created
- ✅ Project template: `_projects/_TEMPLATE_project.md`
- ✅ Publication template: `plans/reports/251221-publication-template.bib`
- ✅ Comprehensive documentation in `plans/reports/`

---

## ⏳ What You Need to Do

### 🔴 Critical (Do Today - 30 min)

1. **Replace Profile Picture**
   - File: `assets/img/prof_pic.jpg`
   - Recommended: 400x400px, professional headshot
   - Format: JPG or PNG

2. **Test Local Build**
   ```bash
   cd /Users/minhtranh/Works/Projects/minhhoang2705.github.io
   docker compose up
   # Visit http://localhost:8080
   ```

### 🟡 Important (This Week - 2-3 hours)

3. **Create 3 Project Files**
   - Copy `_projects/_TEMPLATE_project.md` to:
     - `1_intellirag_system.md`
     - `2_action_retrieval_cctv.md`
     - `3_vietnamese_ocr.md`
   - Fill in details from your CV
   - Delete example projects (1-9_project.md)

4. **Add Your Publication**
   - Open `_bibliography/papers.bib`
   - Delete Einstein examples (lines 72-116)
   - Copy from `plans/reports/251221-publication-template.bib`
   - Paste your publication

5. **Expand About Page**
   - File: `_pages/about.md`
   - Add current role/affiliation (line 5)
   - Expand personal bio (lines 33-54)
   - Update location if needed (lines 12-14)

### 🟢 Optional (This Month - 1-2 hours)

6. **Choose Theme Color**
   - Edit `_sass/_themes.scss`
   - Change `--global-theme-color` variable
   - Options in `_sass/_variables.scss`

7. **Add Google Scholar** (if applicable)
   - Get your Google Scholar ID
   - Add to `_data/socials.yml` (line 18)

8. **Add CV PDF** (optional)
   - Export CV to PDF
   - Save as `assets/pdf/cv.pdf`
   - Uncomment line 23 in `_data/socials.yml`

---

## 📂 Key Files Reference

### Files to Edit
```
✏️ EDIT THESE:
├── _pages/about.md                   # Your homepage bio
├── _projects/
│   ├── 1_intellirag_system.md        # Create from template
│   ├── 2_action_retrieval_cctv.md    # Create from template
│   └── 3_vietnamese_ocr.md           # Create from template
├── _bibliography/papers.bib          # Add your publication
└── assets/img/prof_pic.jpg           # Replace with your photo

🗑️ DELETE THESE:
├── _projects/1_project.md            # Delete all example projects
├── _projects/2_project.md            # (1-9_project.md)
└── ...                               # through 9_project.md
```

### Files Already Configured (Don't Touch)
```
✅ DONE - NO CHANGES NEEDED:
├── _config.yml                       # Configured with TODO markers
├── _data/socials.yml                 # Email, GitHub, LinkedIn added
├── assets/json/resume.json           # Your CV in JSON format
└── _data/cv.yml                      # DELETED (using resume.json)
```

---

## 🚀 Deploy Checklist

Before pushing to production:

- [ ] Local build works: `docker compose up`
- [ ] Profile picture replaced
- [ ] 3 projects created (not examples)
- [ ] Publication added to papers.bib
- [ ] About page bio expanded
- [ ] CV page displays correctly at `/cv/`
- [ ] Publications page shows your paper at `/publications/`
- [ ] Projects page shows your 3 projects at `/projects/`

When ready:
```bash
git add .
git commit -m "Complete portfolio setup with CV, projects, and publication"
git push origin main
```

Site will auto-deploy to: https://minhhoang2705.github.io

---

## 📊 Progress Summary

| Category | Status | Progress |
|----------|--------|----------|
| Configuration | ✅ Complete | 100% |
| Resume/CV | ✅ Complete | 100% |
| Social Media | ✅ Complete | 100% |
| Templates | ✅ Complete | 100% |
| Profile Picture | ⏳ Pending | 0% |
| Projects | ⏳ Pending | 0% |
| Publications | ⏳ Pending | 0% |
| About Page | ⏳ Partial | 30% |
| **Overall** | ⏳ In Progress | **65%** |

---

## 📚 Documentation

All documentation in `plans/reports/`:
- `251221-portfolio-setup-summary.md` - Complete setup guide
- `251221-resume-conversion-complete.md` - Resume conversion details
- `251221-publication-template.bib` - Publication BibTeX template

---

## 🆘 Quick Help

**Q: How do I test locally?**
```bash
docker compose up
# Visit http://localhost:8080
```

**Q: How do I add a project?**
1. Copy `_projects/_TEMPLATE_project.md`
2. Rename to `1_yourproject.md`
3. Fill in the TODO markers
4. Replace example images

**Q: How do I change the theme color?**
Edit `_sass/_themes.scss`:
```scss
--global-theme-color: var(--your-color);
```

**Q: Where's my CV displayed?**
- Full CV: https://minhhoang2705.github.io/cv/
- About page: https://minhhoang2705.github.io/ (homepage)

---

## 📞 What to Do Next

**Right now (5 min)**:
1. Replace `assets/img/prof_pic.jpg` with your photo

**Today (30 min)**:
1. Test: `docker compose up`
2. Verify everything looks good at `localhost:8080`

**This week (2-3 hours)**:
1. Create 3 project files
2. Add your publication
3. Expand bio

**Then deploy**:
```bash
git add .
git commit -m "Launch portfolio"
git push origin main
```

✨ **Your portfolio will be live in ~5 minutes after push!**

---

**Need help?** Check the detailed documentation in `plans/reports/251221-portfolio-setup-summary.md`
