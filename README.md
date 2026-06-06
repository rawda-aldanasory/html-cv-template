# html-cv-template
ATS-Friendly CV Template Built with HTML &amp; CSS Deploy on Netlify and export to PDF from the browser.
# ATS-Friendly CV Template

A simple ATS-friendly CV template built with HTML & CSS.

Use it as:

* A PDF resume for job applications
* A personal CV website
* A shareable resume link that stays the same even after updates

---

# Quick Start (Recommended for Non-Technical Users)

You don't need to know HTML or CSS.

1. Open `index.html`
2. Copy the entire file content
3. Paste it into ChatGPT or any AI assistant
4. Send your CV information and ask:

"Replace all placeholder content with my information. Keep the HTML structure unchanged."

5. Replace the content inside `index.html` with the updated version
6. Save the file

That's it.

**Important:** Do not modify `style.css` unless you want to change the design.

---

# Editing the Template Manually

Open `index.html` using:

* VS Code
* Cursor
* Windsurf
* Any text editor

Search for:

`TODO`

Every place marked with `TODO` should be updated with your information.

Examples:

* Name
* Job title
* Email
* LinkedIn
* Projects
* Skills
* Experience

---

# Preview Your CV

You don’t need any tools or installation.
After editing:

Just open the project folder:

- Find `index.html`
- Double-click it
- It will open in your browser automatically

### What to check
- Make sure your name and info appear correctly
- Check that links (LinkedIn / Portfolio) open properly
- Scroll through the whole CV to ensure nothing is broken

---

# Export as PDF

1. Open the CV in your browser
2. Press `Ctrl + P`
3. Select "Save as PDF"
4. Save the file

You now have an ATS-friendly PDF resume.

---

# Publish Online with Netlify

1. Keep both files together:

* index.html
* style.css

2. Open Netlify
3. Choose "Add new project"
4. Drag and drop the entire project folder

Do NOT upload individual files.

Upload the folder containing both files.

---

# Common Mistakes

### My styles disappeared

Make sure:

* `index.html`
* `style.css`

are inside the same folder.

---

### My links don't open correctly

Update BOTH:

* the text users see
* the URL inside `href=""`

Example:

```html
<a href="https://www.linkedin.com/in/rawdamo7amed/">
  linkedin.com/in/rawdamo7amed/
</a>
```

### The website looks broken

Check if you accidentally removed:

```html
<section>
</section>
```

or

```html
<div>
</div>
```

If something breaks, compare your file with the original template.
