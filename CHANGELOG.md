# Changelog

All user-facing changes to Docalto, newest first. Docalto is in testing on Google Play. Per-version notes are in [release-notes/](release-notes/) and on the [Releases](https://github.com/1tordroid/Docalto-Releases/releases) page. The changelog is also on the website: https://docalto.tordroid.com/changelog/

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
