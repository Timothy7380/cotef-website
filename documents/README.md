# COTEF Documents & Reports

Every file uploaded to this `documents` folder appears automatically in the
**Documents & Reports** section of the website, with a download button.

## How to add a document
1. Open https://github.com/Timothy7380/cotef-website/tree/main/documents
2. Click **Add file → Upload files**, drop in the PDF / Word / Excel / PowerPoint file, then **Commit changes**.
3. The website updates within about a minute.

Tip: name files clearly, e.g. `ESOHE-2026-Impact-Report.pdf` — the website turns
the file name into the title ("Esohe 2026 Impact Report").

## Optional: nicer titles, dates and descriptions
Edit `_info.json` in this folder and add an entry per file name, for example:

```json
{
  "ESOHE-2026-Impact-Report.pdf": {
    "title": "ESOHE 2026 Impact Report",
    "description": "Outcomes from our September 2026 outreach",
    "date": "2026-09",
    "category": "Reports"
  }
}
```

To remove a document, open it in this folder, click the **⋯** menu → **Delete file**, then commit.
