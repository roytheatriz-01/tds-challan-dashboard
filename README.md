# TDS Challan Register

Company-wise and section-wise register of TDS challans (ITNS 281): upload challan copies (PDF or image), see month-wise deposit status against due dates, section-wise totals, and export to CSV.

## Two ways to use it

**On GitHub Pages / opened directly (`index.html`)**
Challans and their files are saved in the browser's own storage (IndexedDB) on that computer only.
- Use **Backup** regularly; it downloads one `.json` file with all challans, companies and challan copies.
- Use **Restore** to load a backup on another computer or browser.
- Clearing browser data deletes the register, so keep backups.

**On claude.ai (shared with the team)**
https://claude.ai/artifact/KDmk5eatkjrho5CtFo7iiS — data and files are stored centrally and shared with everyone the page is shared with.

## Due dates used
- 7th of the following month; 30 April for March deductions.
- 30 days from the end of the month for 194IA, 194IB, 194M, 194S.

## Publish on GitHub Pages
Repo → Settings → Pages → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save. The site appears at `https://<username>.github.io/<repo>/`.
