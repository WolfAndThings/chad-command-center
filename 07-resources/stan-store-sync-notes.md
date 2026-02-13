# Stan Store Internal Course QA Notes

## 2026-02-13

### Scope Completed
- Audited internal editor pages for Courses 1-4:
  - AI Visual Foundations
  - The Prompt Arsenal
  - ChatGPT Visual Production
  - The Grit System
- Reviewed module stacks, lesson naming readability, heading-style consistency, and image presence.
- Cleaned module naming/spacing issues found during the pass.

### Internal URLs Audited
- `https://admin.stan.store/stores/1015996/page/course/4364612?order=0&tab=product&skipModal=true` (Course 1)
- `https://admin.stan.store/stores/1015996/page/course/4354920?order=2&tab=product&skipModal=true` (Course 2)
- `https://admin.stan.store/stores/1015996/page/course/4364576?order=3&tab=product&skipModal=true` (Course 3)
- `https://admin.stan.store/stores/1015996/page/course/4364813?order=6&tab=product&skipModal=true` (Course 4)

### Fixes Applied
- **Course 3 (ChatGPT Visual Production)**
  - Removed accidental draft placeholders (`Next Module!`) so only intended modules remain.
  - Renamed module heading from `STYLE EXTRACTION` to `Reference Lock & Style Control` for cleaner hierarchy.
  - Kept `Motion-Ready Frames (ChatGPT to Video)` naming in place for clearer structure.
- **Course 2 (The Prompt Arsenal)**
  - Renamed `Module 2: EDITORIAL & GRIT` to `Editorial & Grit`.
  - Renamed `Module 3:LIFESTYLE & UGC` to `Lifestyle & UGC` (spacing + title cleanup).

### QA Results By Course
- **Course 1:** Module stack loads, headings/readability acceptable, product thumbnail image present.
- **Course 2:** Module names cleaned, stack loads cleanly, product thumbnail image present.
- **Course 3:** Draft placeholders removed, module headings cleaned, stack stable, product thumbnail image present.
- **Course 4:** Module stack and headings are clean, product thumbnail image present.

### Image Check
- In each audited course editor, Thumbnail tab loads with existing image selected (`Choose Image` empty-state not shown).

### Status
- ✅ Internal course/module/lesson pass completed for Courses 1-4
- ✅ Naming/spacing cleanup applied where needed
- ✅ Images present for audited course thumbnails
