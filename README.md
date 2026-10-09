# HTML Review

A small, dependency-free HTML reference project. Each page is intended to focus
on one core HTML topic so the examples can be reviewed independently.


## Contributors & Responsibilities

### Muqaddas
- Home page (`index.html`)
- Text page (`text.html`)
- Links page (`links.html`)

### Liz
- Lists page (`lists.html`)
- Tables page (`tables.html`)
- Forms page (`forms.html`)
- Icons
- Quiz

### Muxliss
- Media page (`media.html`)
- Semantic page (`semantic.html`)
- Metadata page (`metadata.html`)


## Project Structure

```text
html-review/
├── index.html          # Main page and links to the topic pages
├── text.html           # Headings, paragraphs, emphasis, quotations, and code
├── links.html          # Hyperlinks, targets, and navigation examples
├── lists.html          # Ordered, unordered, and description lists
├── tables.html         # Table structure, headings, captions, and cells
├── forms.html          # Form controls, labels, validation, and submission
├── media.html          # Images, audio, video, and accessible alternatives
├── metadata.html       # Document head, title, metadata, and viewport settings
├── semantic.html       # Semantic layout elements such as header, main, and footer
├── css/
│   └── style.css       # Shared styles for the pages
└── media/              # Images or other local media used by the examples
```


## What It Needs

- A modern web browser such as Chrome, Firefox, Safari, or Edge.
- No build tool, package manager, server, or external dependency is required.
- Optional: a code editor with HTML validation and formatting support.

The project is currently a scaffold: the HTML pages and stylesheet are present,
but the files still need their examples and shared navigation added.

## Run Locally

Open `index.html` directly in a browser, or use a local server from the project
directory:

Then visit <http://localhost:8000>.

Using a local server is recommended once the project includes local media or
JavaScript, because it matches how files are normally served on the web.

## Completion Checklist

- Add a valid HTML document structure to every page.
- Add a shared navigation menu linking all topic pages.
- Link each page to `css/style.css`.
- Include useful examples and short explanations for each topic.
- Use semantic elements and accessible labels, alt text, and table headings.
- Keep media files inside `media/` and reference them with relative paths.
- Test every navigation link and form control in a browser.
- Check the pages with an HTML validator before considering the review complete.

## Suggested Learning Order

1. `text.html`
2. `links.html`
3. `lists.html`
4. `tables.html`
5. `forms.html`
6. `media.html`
7. `metadata.html`
8. `semantic.html`

This order moves from basic content and navigation to structured data, user
input, media, document metadata, and page organization.
