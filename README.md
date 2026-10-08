# Psychiatric Screening Tools & Rating Scales (NURS 632)

A single-page reference of commonly used psychiatric screening tools and rating scales, organized by diagnostic category and age group (children/adolescents vs. adults), with primary references. Compiled for NURS 632, Pathogenesis of Mental Disorders, George Mason University.

## Publish with GitHub Pages

1. Create a new public repository on GitHub (for example, `nurs632-rating-scales`).
2. Upload `index.html` and this `README.md` to the repository's main branch.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After a minute or two, the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Editing content

All content lives in two arrays near the bottom of `index.html`:

- `DATA` holds the diagnostic categories and their tools. Each tool has:
  - `n` (name), `f` (full name)
  - `a`: age group, where `"c"` = children/adolescents, `"a"` = adults, `"b"` = both
  - `t` (purpose), `r` (rater), `k` (key points)
  - `hy: true` to flag a tool as high-yield, `pr: true` to mark it as proprietary/licensed
  - `refs`: a list of `{ c: "citation", pm: "article title for PubMed search" }`. Leave `pm` out for books and manuals.
- `GUIDES` holds the guideline statements shown at the bottom of the page.

Edit the text, commit, and GitHub Pages republishes automatically.

## Notes

- PubMed links run a title search rather than pointing to a fixed record, so they keep working if PubMed IDs change.
- USPSTF and society guidelines are updated periodically. Review the Guidelines section each semester.
- Cutoffs listed are those reported in the cited validation studies or in common clinical use. Students should confirm them against the original sources before applying them clinically.
