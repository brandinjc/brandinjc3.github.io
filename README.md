# Music & Sound Recording Portfolio

A lightweight, responsive portfolio website designed for a first-year Music & Sound Recording student.

## Files

- `index.html` — the page structure and content
- `style.css` — all visual styling
- `README.md` — setup/customization notes

## Quick customization

Open `index.html` and replace:

- `Your Name`
- `YN.` in the logo
- `your.email@example.com`
- LinkedIn URL
- résumé filename/link
- project descriptions
- skills
- career goals
- image placeholders

## Adding images

Create a folder named `images` and put your images inside it.

Replace a placeholder such as:

```html
<div class="hero-image image-placeholder">
  ...
</div>
```

with:

```html
<img class="hero-image" src="images/studio.jpg" alt="Recording studio console">
```

Always provide useful `alt` text.

## Adding audio

For an audio file stored in your repository, you can use:

```html
<audio controls>
  <source src="audio/my-project.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

For larger portfolios, you can also embed a hosted player from a service that supports your work.

## Contact form

The included form opens the visitor's default email application using `mailto:`.

Replace this line in `index.html`:

```javascript
const recipient = "your.email@example.com";
```

with your actual professional email.

For a true web form that works without the visitor having an email application configured, connect the form to a form-handling service or backend later.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, `README.md`, and any `images`/`audio` folders.
3. In GitHub, open **Settings → Pages**.
4. Under the publishing/source settings, select the branch containing your website (commonly `main`) and the root folder.
5. Save the settings.
6. GitHub will provide your published Pages address.

Keep `index.html` at the top level of the publishing folder.

## Learning tip

Start by changing one thing at a time in `style.css`. Try changing:

- `--accent` for the main color
- `--bg` for the page background
- `--max-width` for content width
- font sizes
- spacing values
- border radius

This makes it easier to understand what each CSS property does.
