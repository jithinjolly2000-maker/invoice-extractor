<div align="center">

# 📄 Invoice Data Extractor

### Paste raw invoice text → get structured fields (invoice #, dates, VAT numbers, amounts)

[![View Live Demo](https://img.shields.io/badge/▶_Try_It_Live-9a3412?style=for-the-badge&logoColor=white)](https://jithinjolly2000-maker.github.io/invoice-extractor/)

![Built with](https://img.shields.io/badge/Built_with-Vanilla_JS-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-none-0a7a52?style=flat-square)
![Privacy](https://img.shields.io/badge/Privacy-100%25_in--browser-17854a?style=flat-square)
![Hosting](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=flat-square&logo=github)

</div>

---

Paste the text of an invoice (from a PDF copy-paste, an email, or OCR output) and the tool
pulls out the structured fields using pattern rules — then lets you copy them as JSON or a CSV row.

## ✨ What it extracts

- **Invoice number** (handles `INV-`, `Rechnung`, `Facture`, `Fattura` labels)
- **Invoice date** and **due date** (multiple date formats)
- **EU VAT numbers** (all member-state prefixes, normalised)
- **Currency**, **VAT amount**, and **total**
- Plus a catch-all list of every date and every money amount found

## ⚠️ Rule-based, not magic

Extraction uses regular-expression rules, so it works best on reasonably structured text and
should always be **reviewed before use**. It's a fast first pass that saves manual re-keying,
not a guaranteed parser for every invoice layout.

## 🔒 Private by design

Text is parsed locally in your browser — **nothing is uploaded**. Paste a real invoice, or click **Load sample**.

## 🧰 Tech

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no dependencies, one `index.html`
- Copy results as **JSON** or a **CSV row** for pasting into a spreadsheet
- Hosted free on **GitHub Pages**

## ▶️ Run locally

```bash
start index.html      # Windows — no build step
```

<div align="center">

---

**Built by Jithin J** · [GitHub](https://github.com/jithinjolly2000-maker) · [LinkedIn](https://www.linkedin.com/in/jithin2k)

</div>
