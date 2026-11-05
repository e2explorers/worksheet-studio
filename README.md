# Earth Science Journal Editor

A reusable, browser-only PDF coloring, annotation, and download app for Earth Science students.

## Publish to GitHub Pages

1. Create a public GitHub repository, for example `earth-science-journal-editor`.
2. Add **index.html** to the root of the repository's default `main` branch. Upload `README.md` as well if desired. Do not upload the ZIP file itself.
3. Open **Settings → Pages** and select **Deploy from a branch**, `main`, `/ (root)`, then **Save**.
4. Check the **Actions** tab for a successful Pages build and deploy. The URL is `https://YOUR-USERNAME.github.io/earth-science-journal-editor/`.
5. Share the URL in Google Classroom as Material. Students upload their own PDF or use a teacher-provided PDF downloaded from Classroom.

## Student workflow

1. Open the website and use **Open a PDF** to load a worksheet saved to the device.
2. Select **Fill area** to color closed white shapes, or **Color / draw** for hand coloring; use **Add text** to place responses.
3. Use **Undo / Redo** to correct work. Switch pages with Previous / Next.
4. Use **Save draft** to download an `.earthjournal` file containing the original worksheet and annotations. Reopen that file later with **Open saved draft**.
5. Use **Download finished PDF** to save a separate PDF with all pages and student annotations. Attach this PDF to the Google Classroom assignment when requested.

## Notes and limitations

- **Privacy:** No student answers or uploaded documents are sent to our own server. Edits take place locally in the browser. GitHub only hosts the website itself.
- **Dependencies:** The website loads PDF.js 3.11.174 and pdf-lib 1.17.1 from Cloudflare's CDN, so internet is needed at first load. There is no server/database account to configure.
- **Fill bucket:** Best for solid black-and-white outlines. A shape with an open gap may spill into the surrounding page; large fills are stopped. For detailed illustrations, use Brush. Light-gray printed elements may be affected depending on fill sensitivity.
- **Text:** Click on a spot to add a typed response. Clicking near an existing text annotation with the Text tool allows editing it. Longer lines automatically wrap within page width.
- **Zoom:** Only changes display size, not the output document.
- **Undo / redo:** Works per page. Clear page is irreversible.
- **Save:** Work is not automatically saved to a cloud account or across devices. Use Save draft or Download finished PDF before closing the tab.
- **PDF export:** Drawings are flattened into the PDF as images while the original PDF pages remain underneath. Some unusual rotated or encrypted PDFs may not export correctly.
- **Source PDF:** This website contains **no student worksheet files**. Provide students the PDF separately so they can upload their own copy. Do not share edit permission for a master document.
