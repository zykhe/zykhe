# zykhe

### about
quietly building in a world of noise, finding beauty in simplicity and meaning in creation.

## about this site

This website embraces a 2003 aesthetic with clean minimalism - no JavaScript, no tracking, no build process. Just pure HTML and CSS that loads instantly and works everywhere.

The design is inspired by early web design with modern touches:
- Courier font for that authentic early-web feel
- Simple borders and structured layout
- Focus on content over chrome
- Semantic HTML with minimal styling

## adding a new post

This site uses a simple static approach for posts. To add a new post:

1. **Create a new HTML file** in the `posts/` directory:
   ```
   cp posts/template.html posts/your-post-title.html
   ```

2. **Edit the new file** and replace the placeholders:
   - `POST_TITLE` - Your post title
   - `POST_DATE` - Publication date (YYYY-MM-DD format)
   - `POST_TAGS` - Tags like #web #code #philosophy
   - `POST_CONTENT` - Your post content in HTML format

3. **Update the homepage** by adding your post to `index.html`:
   ```html
   <div class="post-item">
       <a href="posts/your-post-title.html" class="post-title">Your Post Title</a>
       <div class="post-date">2025-10-29</div>
       <div class="post-excerpt">Brief excerpt of your post...</div>
   </div>
   ```

4. **Add the post at the top** of the post list in the `#posts` section to maintain chronological order.

## writing guidelines

- Keep paragraphs focused and relatively short
- Use semantic HTML tags (`<p>`, `<h3>`, etc.) for structure
- No JavaScript needed - just pure HTML
- Consider the 2003 aesthetic: clean, structured, content-focused
- Tags should be lowercase and prefixed with # (e.g., #code #philosophy)

## file structure

```
├── index.html          # Main homepage
├── style.css           # Site styling
├── README.md           # This file
├── favicons/           # Favicon files
│   ├── apple-touch-icon.png
│   ├── favicon-96x96.png
│   ├── favicon.ico
│   ├── favicon.svg
│   ├── site.webmanifest
│   ├── web-app-manifest-192x192.png
│   └── web-app-manifest-512x512.png
└── posts/              # Blog posts directory
    ├── template.html   # Post template
    └── unown-manifesto.html
```

## validation

This site aims to have valid HTML and CSS. You can check validation using the links in the footer or by:
- HTML: https://validator.w3.org/check/referer
- CSS: https://jigsaw.w3.org/css-validator/check/referer

## deployment

This site is designed for GitHub Pages but can be hosted on any static web server. Simply push the files to your repository and enable GitHub Pages in your repository settings.
