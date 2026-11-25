# Changelog

All user-facing changes to Docalto, newest first. Per-version notes are in [release-notes/](release-notes/) and on the [Releases](https://github.com/1tordroid/Docalto-Releases/releases) page. The changelog is also on the website: https://docalto.tordroid.com/

This repository starts at **1.1.0** (versionCode 2), imported on 1 November 2026. There is no 1.0.x tag or version name in the git history. Version codes that shipped under a version name are listed with that name. **1.3.0** was development work on this branch. It was renamed to **2.0.0** before any 1.3.0 release.

## 2.6.0

versionName **2.6.0**, versionCode **16**. 25 November 2026 (Asia/Calcutta, IST).

### Highlights

- **Edit text in photos:** change words in a scanned page or a photo in your PDF, and keep the original font, size and colour. OCR and inpainting run on the phone. Style reading is available when Online mode is on.
- **Online AI, off until you allow it:** a switch on Home and in Settings covers AI, translation and cloud tools. When you turn it on, AI can step into tools, flows and search. Docalto asks before it goes online.
- **Your own AI key:** Gemini, Claude, OpenAI, Grok (xAI), or an OpenAI-compatible model. Keys stay encrypted on the phone. No Docalto account. Gemini accepts both older AIza keys and new AI Studio auth keys (AQ.). Gemini always uses the native Google API. The model list is fetched live, the newest stable flash is the default, and a retired model is replaced automatically.

### Also in this release

- A cleaner Home, Files, Tools and Settings, in light or dark, with the phone's font on by default.
- AI recommends the next step for a recent file, worked out on the phone. "Why this?" explains it, and "Not now" hides it for that file.
- My recommendation on Compress: a suggested level with a before and after size estimate, Use this or Keep mine.
- Search every tool, file, recent and flow by voice or text. A request that names tools can run in one go, or go to the AI assistant, which asks before going online.
- AI steps in flows, a clearer flow builder, and new ready-made flows.
- A Home widget for Quick Scan and Recent files, and app shortcuts for Scan, Edit image text and Search.
- An encrypted local copy of your work, unfinished jobs, flows and settings in Documents/Docalto. After a clear data or a reinstall, Docalto can restore it, or delete it after you confirm.
- A password-protected local backup of settings and flows. Files, keys and purchases are not included.
- 75 tools in All Tools. A short What's new sheet for people updating from 2.5, and a three-screen first-run tour.
- When you are online, Docalto checks Google Play for updates. If a newer version exists, or no check has succeeded for 45 days, it asks you to update first. Your files are never touched by this, and root alone never blocks the app.
- A modified or unofficial copy is blocked, with links to Google Play and tordroid.com. Root, a failed integrity check alone, or a debug build signed with our key does not trigger this.
- Terms of use are accepted on first run and from About. The licence forbids commercial reuse, rebranding, or use of the code, design or assets in other apps without written permission.
- If the app closes unexpectedly, a short report can be kept on the phone and shared by hand; nothing is sent on its own.

## 2.5.1

versionName **2.5.1**, versionCode **15**. 25 November 2026.

- Fixed: a Google Play install of 2.5.0 closed as soon as it opened, because ONNX Runtime's start-up component was listed in the app even when the layout OCR add-on had not been downloaded.

## 2.5.0

versionName **2.5.0**, versionCode **14**. 24 November 2026. Includes the 2.2.0 fixes.

- New simpler design: a bottom bar with Home, Files, a centre Scan button, Tools and Flow; Settings at the top right; big labelled tiles; Figtree and Noto Sans Devanagari; all seven colour themes with deeper fills and soft icon tints (Lime is now #4A7312 for contrast).
- Ask across files: up to 100 PDFs indexed on the phone, answers with file and page; optional web-searched answers on your own AI key.
- Ask about charts and pictures, and Rebuild layout with AI (scans to Word with headings, lists and tables), on your own key.
- Audio overview: two voices talk through a PDF; natural voices from a Gemini or ChatGPT key, otherwise the phone's voices.
- Layout OCR (PaddleOCR) reads columns and mixed scripts in order. On Google Play it comes as an add-on from Play on first use, with its size shown before the download (about 31 MB, plus about 7 MB for each extra script), so the app itself stays near the 2.2.0 size. The website copy keeps the one-time checked download.
- Pen: pen-only mode, pressure, and Snap shapes (lines, boxes and ovals). Reading view spacing, width, serif and justify. Tabs for open files.
- Accessibility check with fixes and a tag editor; Print check for PDF/X-4 basics.
- Signatures with a timestamp now add long-term validation (certificates, revocation data and a document timestamp).
- Forms: totals and formulas update as you type; static XFA forms fill everywhere; fill saves as an incremental update.
- Compare: Word, text, sheet and slides files as well as PDFs, and a Word file with tracked changes.
- Batch: chain several steps on each file with name and size filters.
- "Docalto: Save as PDF" in every app's Print menu, saved to Downloads/Docalto.
- Work and school devices: administrators can turn off online features, online AI, web search, downloads, or limit AI providers (managed configuration).
- Online AI retries briefly on busy or failed connections and sends smaller page pictures on mobile data.
- Fixed: saving many photos as one PDF could fail on large sets.
- Large-file benchmark published in docs/BENCHMARK.md.

## 2.1.0

versionCode 12. Released 24 November 2026 to internal and closed testing on Google Play.

### What's new

- **Seven colour themes:** Lime, Ocean, Rose, Amber, Violet, Mint and Coral, in Settings next to the app icon.
- **Recent on Home:** your last 3 files at the bottom of Home, with View more. Settings is one tap away on every tab.
- **Study tools:** flashcards, a quiz and an outline map made on the phone from a PDF's own text, with Save study notes.
- **More reading scripts:** text reading for Arabic, Urdu, Bengali, Tamil, Telugu, Gujarati, Punjabi, Kannada, Malayalam, Odia and Russian. Each is a one-time download after you agree, then works offline.
- **Pro Camera:** Macro, Night and adjustable corners, plus Scanner Enhance.
- **New tools:** Measure (distance, area and perimeter at a drawing scale), Reading view, Make a fillable form, Pictures in PDF, Web page to PDF, a visual change report in Compare, and review file (XFDF) import.
- **Office export:** PDF to Word, Excel and PowerPoint now export every page.
- **Fewer false blocks:** root, LSPosed or Xposed on the phone no longer stop the app; only tampering with Docalto itself does.
- **Your language:** What's new shows translated highlights in all 15 app languages, and Why Docalto has new rows and an online and AI section in every language.

### Online and AI, honestly

- **Offline:** every tool, text reading, summaries (Gemini Nano on phones that have it, key sentences on others), Ask this PDF, Study tools and signatures.
- **With your own AI key** (Gemini, Grok, Claude or ChatGPT) and online turned on: chat with PDF, online summary, rewrite, translation and page text reading. Docalto asks before the first use; the key is encrypted on the phone and never backed up.
- **Coming soon** (needs a Docalto server): exact Office layout, sign by link, review by link, and online AI without your own key. These are marked Coming soon in the app and do nothing online.

Full list: https://docalto.tordroid.com/changelog/#v2-1-0

## 2.0.1

Released 24 November 2026 to closed testing on Google Play.

### What's new

- **Scan button.** A new Scan button in the middle of the bottom bar. Scan a document straight to PDF at full quality, or scan a QR code or barcode.
- **Next steps after a scan.** A sheet offers what to do next: save as PDF, extract text, sign, compress, merge, edit, protect or share. A finished file from any tool can go straight into the next tool.
- **Safe links from codes.** A scanned web address shows the full link and asks before opening it (Open, Copy or Cancel). Scanned codes are kept in a history on the phone.
- **Phones without Google Play services** (LineageOS, AOSP and other de-Googled phones) get an in-app camera scanner for documents and codes. Only then does Docalto ask for the camera, and pictures stay on the phone.
- **Voice search.** Search has a mic button: say what you are looking for and the phone's speech app types it in. The app does not ask for microphone permission.
- **What's new screen** in Settings, with this version's changes and the notes from earlier releases. It opens with a Why Docalto card.
- **About.** The Developer row shows Tordroid and opens the Tordroid GitHub page. A new Visit website row opens docalto.tordroid.com.

### Fixes

- Play Store installs no longer show "This copy of Docalto was modified" on newer Android versions (Android 17).
- Saving a PDF from many photos works again, at full original quality.
- Tapping a tool no longer reads its name aloud. "Read labels aloud" is now off by default, and this update turns it off once on phones that had it on.
- The related tools strip no longer covers the Edit PDF tool labels on smaller screens, and folds away on short screens.

### Why Docalto

PC-class PDF tools in one Android app, running offline on your phone with no account and no upload, which very few apps offer.

## 2.0.0

Released 24 November 2026 to closed testing on Google Play.

### New features

- Home, My Files, All Tools and Flow. Home has a full-width All Tools row.
- Flow runs several tools on one file. Ready-made flows are included, and you can save your own.
- Markup (highlight, underline, strike, ink, notes, rectangle) and one-step removal of those marks.
- Bookmarks you can add, rename, nest and reorder.
- Remove hidden details (metadata, scripts, attached files). Remove blank pages. Bates-style page numbers and header lines.
- Find words across recent PDFs. Search more folders from My Files when you allow it.
- Pages on one sheet, split by a size you pick, booklet order, and batch jobs.
- Office export keeps layout. Edit one positioned text run. Replace a plain line and fill header tokens.
- Digital signatures can take a timestamp when the phone is online (only a hash is sent, never the PDF).
- Handwriting recognition. OCR and Office work can wait in a queue.
- Optional app lock with fingerprint or the screen lock. Saved PDF passwords are encrypted.
- Optional All files access, asked for only in My Files. Every tool still works through the file picker without it.
- The new ink D on lime app icon.

### Improvements

- A finished PDF is written to a temporary file before the original is replaced, so a failed save never damages your file.
- Pro tools are free while Docalto is in testing.
- On-device AI and language packs download in the background on Wi-Fi or mobile data, and the screen stays usable.
- English interface, with translations for 14 more languages.
- Light paper, dark and AMOLED black themes with the lime accent.
- Back from My Files, All Tools or Flow returns to Home.

### Fixes

- The app lock and saved passwords work on Android 8.
- A model download no longer holds the screen.

### Compatibility

- Android 8 and later, targets Android 16.
- Ready for phones with 16 KB memory pages.

## 1.2.0

Released 6 November 2026 to closed testing on Google Play.

- Library updates and the Play Store listing.
- Newest build tools and libraries across the app.

## 1.1.1

Released 6 November 2026 to closed testing on Google Play.

- If no ad is available, the tool still runs.
- Sturdier read aloud.

## 1.1.0

The first Docalto release, November 2026 (closed testing on Google Play).

- Merge, split, compress, protect, unlock, images to PDF, Word to PDF, page numbers, watermark, forms, organize pages.
- Edit PDF: text, pen, highlight, whiteout, and a saved signature.
- Scan to PDF, OCR, and translation with an on-device language pack.
- Read aloud, text view, extract images, long image, crop margins, compare two PDFs, Ask this PDF, PDF to PowerPoint.
- Smart tools: on-device summary (Gemini Nano on phones that support it), key details, QR and barcodes, auto-redact, handwriting.
- Image formats: JPEG, PNG, WebP, GIF, HEIC, AVIF, JPEG 2000, JPEG XL, TIFF (including fax Group 3 and Group 4), Photoshop and SVG.
- File Rescue, layered PDF repair, and an isolated sandbox for rare formats.
- Read and edit Office files. Type filters and date groups in Files.
- Verify signatures, including on password-protected PDFs, and PDF/A archive copies.
- Search on Home, Files and Settings. Recent files. Select and Select all in Files.
- A free plan, and Premium monthly, yearly and lifetime.
- Themes and a choice of home-screen icons.
- Translations, and a smaller Play build that uses Play services for OCR and barcodes.
