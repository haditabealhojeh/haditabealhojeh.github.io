# Theses & Supervision page

This update adds a dedicated `/supervision/` page to the al-folio website and adds it to the main navigation as **Theses & Supervision**.

## Files

- `_pages/supervision.md` — page content and sections for current theses, completed theses, and student researchers.
- `_data/navigation.yml` — navigation updated to point to `/supervision/` instead of the previous `/students/` item.

The existing `_pages/students.md` file is not deleted. It remains available at `/students/` if you want to keep that URL, but it is no longer in the main navigation.

## Adding an entry

Copy this template into the relevant section of `_pages/supervision.md` and replace the bracketed fields:

```html
<div class="card mb-3">
  <div class="card-body">
    <h3 class="card-title">[Thesis title]</h3>
    <p class="mb-1"><strong>Student:</strong> [Student name]</p>
    <p class="mb-1"><strong>Degree:</strong> [B.Sc. / M.Sc. / Ph.D.]</p>
    <p class="mb-1"><strong>Role:</strong> [Supervisor / Co-supervisor / Advisor]</p>
    <p class="mb-1"><strong>Status:</strong> [Ongoing / Completed, year]</p>
    <p class="mb-0">[Two- or three-sentence description of the research.]</p>
    <!-- Optional: add a link to a public thesis, paper, project, or student profile. -->
  </div>
</div>
```

Only include student names, photos, or external profile links after confirming that the student is comfortable with public display. Avoid publishing private thesis material or personal contact details.

## Apply

Extract the ZIP into the root of the existing website repository, preserving paths. Review `_data/navigation.yml` before replacing it if you have made any newer navigation changes elsewhere.

```bash
git add _pages/supervision.md _data/navigation.yml
git commit -m "Add theses and supervision page"
git push origin main
```
