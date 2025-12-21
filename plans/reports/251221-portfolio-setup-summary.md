# Portfolio Setup Summary

**Date**: 2025-12-21
**Focus**: Industry-Academic Portfolio (Projects + Publications, No Blog)
**Status**: ✅ Configuration Complete, Ready for Content Population

---

## Changes Made

### 1. Configuration Files Updated

#### `_config.yml` ✅ DONE
**Changes**:
- Disabled blog system (pagination, related posts, search)
- Removed news and books collections
- Disabled Jekyll archives for blog/books
- Added clear ✏️ TODO markers for sections needing review
- Marked analytics/SEO sections as optional

**Key Sections**:
- ✅ Personal info (name, email, description) - already filled
- ✅ Keywords - already configured
- ✏️ Analytics (optional) - marked for later setup
- ✏️ Theme customization - instructions added

**Disabled**:
- Blog name/description cleared
- Pagination disabled
- Related posts disabled
- Posts search disabled
- Blog-related collections removed

#### `_pages/about.md` ✅ DONE
**Changes**:
- Rewrote with TODO markers
- Disabled announcements/news section
- Disabled latest posts section
- Added starter bio with your research interests
- Provided clear instructions for customization

**TODO for user**:
- Replace profile picture (assets/img/prof_pic.jpg)
- Update subtitle with affiliation
- Expand personal bio
- Update location/contact info

#### `_data/socials.yml` ✅ DONE
**Changes**:
- Added comprehensive TODO markers
- Categorized into ESSENTIAL, ACADEMIC, OPTIONAL
- Pre-filled email (minhhtran.work@gmail.com)
- Pre-filled GitHub username (minhhoang2705)
- Disabled RSS icon (no blog)

**TODO for user**:
- Add LinkedIn username (highly recommended)
- Add Google Scholar ID if applicable
- Add ORCID if applicable
- Upload CV PDF to assets/pdf/

#### `_bibliography/papers.bib` ✅ DONE
**Changes**:
- Added comprehensive template section with examples
- Provided 3 templates: Industry/Technical, Academic Papers, Conference Talks
- Documented all custom fields (code, slides, video, website, blog, etc.)
- Marked Einstein examples for deletion

**TODO for user**:
- Delete all Einstein example entries
- Add your publications using provided templates
- Use `selected={true}` to feature on homepage

#### `_projects/_TEMPLATE_project.md` ✅ CREATED
**Created**:
- Complete project template with detailed instructions
- Sections: Overview, Technical Details, Results, Code/Demo, Challenges
- Clear TODO markers throughout
- Instructions for NDA/proprietary work
- Naming conventions and importance levels explained

**TODO for user**:
- Delete example projects (1_project.md through 9_project.md)
- Copy template to create new projects (e.g., 1_rag_system.md)
- Fill in project details using template structure

---

## Files to Delete

### Example Content (Delete After Creating Your Own):
```
_projects/1_project.md through 9_project.md  # Example projects
_data/cv.yml                                  # Not needed (using resume.json)
```

### Already Excluded (No Need to Delete):
```
_posts/          # Blog posts (excluded in _config.yml)
_news/           # News items (excluded in _config.yml)
_books/          # Books collection (excluded in _config.yml)
```

---

## Quick Start Checklist

### Phase 1: Essential Setup (Today)
- [ ] Replace `assets/img/prof_pic.jpg` with your headshot
- [x] ✅ Update LinkedIn username in `_data/socials.yml` - DONE
- [x] ✅ Fill in resume.json with your CV data - DONE
- [ ] Test local build: `docker compose up`
- [ ] Verify site at `http://localhost:8080`

### Phase 2: Content (This Week)
- [ ] Expand bio in `_pages/about.md`
- [ ] Delete example projects (1-9_project.md), create 3-5 real projects using template
- [ ] Delete Einstein entries in papers.bib, add your publication from CV
- [ ] Add profile picture and update location info

### Phase 3: Polish (This Month)
- [ ] Choose theme color in `_sass/_themes.scss`
- [ ] Add Google Scholar ID if applicable
- [ ] Upload CV PDF to `assets/pdf/cv.pdf`
- [ ] Configure analytics (optional)
- [ ] Test mobile responsiveness

---

## File Edit Locations

### High Priority (Edit These First):

1. **`_pages/about.md`**
   - Line 5: Subtitle/affiliation
   - Line 9: Profile picture filename
   - Lines 12-14: Location info
   - Lines 33-54: Your bio and research interests

2. **`_data/socials.yml`**
   - Line 14: LinkedIn username
   - Line 18: Google Scholar ID (if applicable)
   - Line 23: CV PDF path

3. **`_projects/`**
   - Delete: 1_project.md through 9_project.md
   - Copy `_TEMPLATE_project.md` → create your own projects

4. **`_bibliography/papers.bib`**
   - Delete: Lines 72-116 (Einstein examples)
   - Add: Your publications using templates at top

### Medium Priority (Optional Customization):

5. **`_config.yml`**
   - Lines 92-99: Analytics IDs (optional)
   - Lines 44-45: Theme color reference

6. **`assets/img/prof_pic.jpg`**
   - Replace with your headshot

7. **`assets/pdf/`**
   - Add cv.pdf if you want CV download link

---

## Theme Customization (Optional)

### Change Main Color:
Edit `_sass/_themes.scss`:
```scss
--global-theme-color: var(--your-color-choice);
```

Available colors in `_sass/_variables.scss`:
- purple (default)
- pink, red, orange, yellow
- green, cyan, blue, dark

---

## Navigation Structure

Current site pages (as configured):
- **/** - About (homepage)
- **/projects/** - Projects grid
- **/publications/** - Publications list
- **/cv/** - CV page (from resume.json)
- **/repositories/** - GitHub repos (optional)

Removed:
- ~~/blog/~~ - Disabled
- ~~/news/~~ - Disabled
- ~~/books/~~ - Disabled

---

## Build & Deploy

### Local Development:
```bash
docker compose up
# Visit http://localhost:8080
```

### Deploy to GitHub Pages:
```bash
git add .
git commit -m "Configure portfolio for projects + publications"
git push origin main
# GitHub Actions will build and deploy automatically
# Check Actions tab for build status
# Site live at: https://minhhoang2705.github.io
```

---

## Resume.json ✅ DONE

**Location**: `assets/json/resume.json`

**Status**: ✅ COMPLETED - Converted from CV.md

**Completed**:
1. ✅ Parsed markdown resume
2. ✅ Converted to JSON Resume format (https://jsonresume.org/schema)
3. ✅ Filled all sections: basics, work, education, skills, projects, publications
4. ✅ Deleted `_data/cv.yml` (no longer needed)
5. ✅ Updated LinkedIn username in socials.yml

**Sections Populated**:
- ✅ basics: name, label, email, phone, url, summary, location, profiles
- ✅ work: Rainscales (AI Engineer), Quy Nhon AI Center (AI Engineer Intern)
- ✅ education: FPT University (BSc AI, GPA 3.2/4.0)
- ✅ skills: 6 categories (Programming, ML/DL, AI Frameworks, Databases, Cloud/DevOps, Monitoring)
- ✅ projects: IntelliRAG System, Action Retrieval, Vietnamese Text Recognition
- ✅ publications: Vietnamese VQA-NLE Dataset (ICISN 2025)
- ✅ languages: Vietnamese (native), English (IELTS 6.0)
- ✅ interests: AI research areas and technical focus

---

## Next Actions

### Immediate (Do Today):
1. Test local build: `docker compose up`
2. Replace prof_pic.jpg
3. Add LinkedIn to socials.yml
4. Verify site works at localhost:8080

### This Week:
1. Create 3-5 project files from template
2. Add your publications to papers.bib
3. Expand about.md bio
4. Provide resume markdown for JSON conversion

### This Month:
1. Choose/customize theme color
2. Add CV PDF
3. Configure Google Scholar ID
4. Test on mobile devices
5. Push to production

---

## Questions/Blockers

None currently. Awaiting:
- ~~User's resume markdown for resume.json conversion~~ ✅ DONE
- ~~User to add social media links~~ ✅ DONE (LinkedIn added)
- User to replace profile picture
- User to create project files from template
- User to add publication to papers.bib

---

## Summary

**What's Done**:
- ✅ Blog/news system completely disabled
- ✅ Config cleaned and marked with TODO
- ✅ About page rewritten with starter content
- ✅ Project template created with examples
- ✅ Publication template with industry focus
- ✅ Social media config with clear instructions
- ✅ All unnecessary sections excluded

**What User Needs to Do**:
1. Edit marked ✏️ TODO sections
2. Delete example content
3. Add real projects (3-5)
4. Add real publications
5. Replace profile picture
6. Test locally before pushing

**Architecture**:
- Focus: Projects (industry) + Publications (academic)
- No blog, no news, no books
- Simple, clean, professional portfolio
- Ready for production deployment

**Estimated Time to Launch**:
- Minimal viable: 2-3 hours (basic bio, 2-3 projects, profile pic)
- Polished: 1 week (full content, customization, testing)
