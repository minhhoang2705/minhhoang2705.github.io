# Resume Conversion Complete

**Date**: 2025-12-21
**Status**: ✅ SUCCESS

---

## Completed Tasks

### 1. Resume.json Conversion ✅
**Source**: `/Users/minhtranh/Downloads/CV.md`
**Destination**: `assets/json/resume.json`

**Converted Sections**:
- ✅ **Basics**: Name, label, email, phone, location, profiles (LinkedIn, GitHub)
- ✅ **Work Experience**:
  - Rainscales (AI Engineer, Feb 2025 - Aug 2025)
  - Quy Nhon AI Center (AI Engineer Intern, Sep 2023 - Dec 2023)
- ✅ **Education**: FPT University (BSc AI, GPA 3.2/4.0, Jan 2022 - Jan 2025)
- ✅ **Skills**: 6 categorized skill groups
  - Programming Languages (Python, C)
  - ML/DL (PyTorch, TensorFlow, etc.)
  - AI Frameworks (LangChain, LangGraph, etc.)
  - Databases (PostgreSQL, Milvus, Qdrant, etc.)
  - Cloud & DevOps (GCP, Docker, K8s, Terraform)
  - Monitoring (Prometheus, Grafana, Loki, etc.)
- ✅ **Projects**: 3 major projects
  - IntelliRAG System (cloud-native RAG platform)
  - Action Retrieval from CCTV Footage
  - Vietnamese Text Recognition
- ✅ **Publications**:
  - "An Automated Pipeline for Constructing a Vietnamese VQA-NLE Dataset" (ICISN 2025)
- ✅ **Languages**: Vietnamese (native), English (IELTS 6.0 - B2)
- ✅ **Interests**: AI research areas (LLMs, VLMs, Multimodal Learning, RAG, etc.)

### 2. Social Media Links Updated ✅
**File**: `_data/socials.yml`
- ✅ Email: minhhtran.work@gmail.com
- ✅ GitHub: minhhoang2705
- ✅ LinkedIn: tranhminh8464

### 3. Cleanup ✅
- ✅ Deleted `_data/cv.yml` (no longer needed)

---

## What's Now Displayed on Your CV Page

Your `/cv/` page will automatically display:

### Personal Info
- Name: Tran Hoang Minh
- Label: AI Research Engineer
- Location: Ho Chi Minh City, Vietnam
- Email: minhhtran.work@gmail.com
- Phone: +84-967-628-624
- LinkedIn & GitHub links

### Summary
Professional summary highlighting your AI/ML expertise, focusing on CV, NLP, LLMs, and Multimodal ML.

### Work Experience (2 positions)
1. **AI Engineer at Rainscales** (Feb 2025 - Aug 2025)
   - Face authentication system (10% accuracy improvement)
   - Pipeline with DeepFace, InsightFace, Milvus
   - API endpoints for model deployment

2. **AI Engineer Intern at Quy Nhon AI Center** (Sep 2023 - Dec 2023)
   - Deep learning optimization (15% accuracy increase)
   - Vietnamese OCR with PaddleOCR
   - Data labeling and validation

### Education
- **FPT University** - BSc in Artificial Intelligence
- GPA: 3.2/4.0
- Jan 2022 - Jan 2025
- Coursework: ML, DL, CV, NLP, Data Science, etc.

### Skills (6 Categories)
With visual icons and organized keywords for each category.

### Projects (3 Major Projects)
Each with summary, highlights, and technology keywords.

### Publications
Your ICISN 2025 paper with full citation.

### Languages
Vietnamese (native), English (professional - IELTS 6.0)

### Research Interests
AI focus areas with icons and keywords.

---

## Next Steps

### Immediate (Do Now):

1. **Test Local Build**:
   ```bash
   docker compose up
   # Visit http://localhost:8080/cv/
   ```

2. **Replace Profile Picture**:
   - Add your photo to: `assets/img/prof_pic.jpg`
   - Recommended: Square crop, professional headshot, 400x400px minimum

3. **Add Your Publication to papers.bib**:
   ```bibtex
   @inproceedings{duong2025automated,
     title={An Automated Pipeline for Constructing a Vietnamese VQA-NLE Dataset},
     author={Duong, Truong-Binh and Tran, Hoang-Minh and Le-Nguyen, Binh-Nam and Duong, Dinh-Thang},
     booktitle={Proceedings of the Fifth International Conference on Intelligent Systems and Networks (ICISN 2025)},
     series={Lecture Notes in Networks and Systems},
     volume={1596},
     year={2025},
     publisher={Springer, Singapore},
     selected={true},  % Shows on homepage
     abstract={Your paper abstract here}
   }
   ```

4. **Create Project Files from Your CV**:
   Copy `_projects/_TEMPLATE_project.md` three times:
   - `1_intellirag_system.md` (IntelliRAG)
   - `2_action_retrieval_cctv.md` (Action Retrieval)
   - `3_vietnamese_ocr.md` (Vietnamese Text Recognition)

   Use the template structure, fill in details from your CV.

### This Week:

1. **Expand About Page Bio**:
   - Add your current role/affiliation
   - Expand on research interests
   - Add what you're currently working on

2. **Delete Example Projects**:
   ```bash
   rm _projects/1_project.md
   rm _projects/2_project.md
   # ... through 9_project.md
   ```

3. **Optional: Add Google Scholar**:
   If you have a Google Scholar profile, add ID to `_data/socials.yml`

### Ready to Deploy:

```bash
git add .
git commit -m "Add complete CV and configure portfolio"
git push origin main
```

---

## Verification Checklist

Before pushing to production:

- [ ] Tested locally: `docker compose up`
- [ ] CV page displays correctly: `http://localhost:8080/cv/`
- [ ] About page shows updated info
- [ ] Profile picture replaced
- [ ] Projects page has your 3 projects (not example projects)
- [ ] Publications page shows your paper
- [ ] Social media icons link correctly

---

## File Structure Summary

```
minhhoang2705.github.io/
├── _config.yml                    ✅ Configured (blog disabled)
├── _pages/
│   └── about.md                   ✅ Updated with TODO markers
├── _data/
│   ├── socials.yml                ✅ LinkedIn, GitHub, email added
│   └── cv.yml                     ✅ DELETED (using JSON Resume)
├── _projects/
│   ├── _TEMPLATE_project.md       ✅ Template created
│   └── 1-9_project.md             ⏳ TODO: Delete and replace
├── _bibliography/
│   └── papers.bib                 ⏳ TODO: Delete Einstein, add your paper
├── assets/
│   ├── img/
│   │   └── prof_pic.jpg           ⏳ TODO: Replace with your photo
│   └── json/
│       └── resume.json            ✅ COMPLETED - Your CV in JSON format
└── plans/reports/
    ├── 251221-portfolio-setup-summary.md      ✅ Main summary
    └── 251221-resume-conversion-complete.md   ✅ This file
```

---

## Summary

✅ **Resume conversion: COMPLETE**
✅ **Social media: CONFIGURED**
✅ **CV page: READY**

⏳ **Remaining**:
- Replace profile picture
- Create 3 project files
- Add publication to papers.bib
- Test locally
- Deploy

**Estimated Time to Launch**: 2-3 hours (to complete remaining tasks)
