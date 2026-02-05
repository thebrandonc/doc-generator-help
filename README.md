
[!WARNING]                                                                                                           
🚧 This page is currently under construction and will be published by end of day 2/5/26


# Doc Generator - Help & Tutorials

Learn how to use Doc Generator to automatically create Google Docs from your spreadsheet data.

## Quick Links

- [Get the Add-on (Free)](MARKETPLACE_URL_HERE)
- [Upgrade to Pro](GUMROAD_URL_HERE)
- [Report an Issue](SUPPORT_URL_HERE)

---

## Video Tutorials

### Getting Started (Free)

| | |
|---|---|
| **1. Getting Started** | **2. Setting Up Your Template** |
| [![Getting Started](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) | [![Template Setup](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) |
| Open the add-on and navigate the sidebar. | Create a Google Doc template with `{{placeholders}}` and connect it. |

| | |
|---|---|
| **3. Understanding Variables** | **4. Generating Documents** |
| [![Variables](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) | [![Generate](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) |
| See which variables match between your template and spreadsheet. | Generate documents and understand the run log. |

| |
|---|
| **5. Automating Generation** |
| [![Automation](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) |
| Set up automatic generation on form submit or a schedule. |

---

### Pro Features

| | |
|---|---|
| **6. Custom Output Folders** | **7. PDF Export** |
| [![Custom Folders](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) | [![PDF Export](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) |
| Save generated documents to a specific Google Drive folder. | Automatically create PDF copies of each document. |

| | |
|---|---|
| **8. Auto-Email Setup** | **9. Complete Pro Workflow** |
| [![Auto-Email](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) | [![Pro Workflow](THUMBNAIL_URL_HERE)](VIDEO_URL_HERE) |
| Send generated PDFs to recipients automatically. | Full walkthrough combining all Pro features. |

---

## FAQs

<details>
<summary><strong>How do I create a template?</strong></summary>

Create a Google Doc and add placeholders using double curly braces: `{{Name}}`, `{{Email}}`, `{{Address}}`, etc. These must match your spreadsheet column headers exactly (case-sensitive).

</details>

<details>
<summary><strong>Why are some variables showing as "missing"?</strong></summary>

Variables show as missing when they exist in your template but not in your spreadsheet (or vice versa). Click "Add missing columns" to automatically create the missing columns, or update your template to match your sheet headers.

</details>

<details>
<summary><strong>What's the difference between Form and Schedule automation?</strong></summary>

- **Form Submit**: Triggers when a Google Form adds a new row to your sheet. Best for real-time processing of form responses.
- **Schedule**: Runs every X minutes (5, 10, 15, 30, or 60) to process any new rows. Best for batch processing or when data comes from other sources.

</details>

<details>
<summary><strong>Why did some rows get "Skipped"?</strong></summary>

Rows are skipped if they already have a value in the "Output Doc URL" column. This prevents duplicate documents from being created. To regenerate a document, clear the URL from that cell.

</details>

<details>
<summary><strong>What are the system columns?</strong></summary>

Doc Generator adds these columns automatically:
- **Output Doc URL**: Link to the generated document
- **Status**: Queued, Generated, Error, or Skipped
- **Generated At**: Timestamp of when the doc was created
- **Error**: Error message if something went wrong

Don't delete these columns or the add-on won't work correctly.

</details>

<details>
<summary><strong>Is there a limit on how many documents I can generate?</strong></summary>

Each run processes up to 50 rows. If you have more pending rows, run generation again or enable automation to process them over time. There's no overall limit on total documents.

</details>

<details>
<summary><strong>Can I use different templates for different sheets?</strong></summary>

Yes! Each sheet tab can have its own template and automation settings. Use the sheet selector dropdown in the sidebar to switch between sheets and configure each one independently.

</details>

<details>
<summary><strong>What's included in Pro?</strong></summary>

Pro unlocks:
- **Unlimited automations** (free tier limited to 1 sheet)
- **Custom output folders** - save docs to any Google Drive folder
- **PDF export** - automatically create PDF copies
- **Auto-email** - send PDFs to recipients with customizable templates

</details>

<details>
<summary><strong>How do I upgrade to Pro?</strong></summary>

[Click here to upgrade](GUMROAD_URL_HERE) and unlock all Pro features instantly.

</details>

---

## Support

Having issues? [Contact support](mailto:YOUR_EMAIL_HERE) or [report a bug](SUPPORT_URL_HERE).

---

## License

This software is licensed under the [Polyform Shield License](LICENSE). You may view and use this software but may not use it to compete with us.
