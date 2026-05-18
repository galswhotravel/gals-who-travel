# Rules
- Never use data:img source for <img> tags, always use a relative path to an image file.
- Always use pure HTML, don't populate content from JS unless it's dynamic content that requires it. 
- for static assets like images, put them in assets/images
- for shared styling (e.g. header/footer, tour cards), put them in assets/css/styles.css
- Keep styling reusable as much as possible. Anything not reusable should stay in that specific .html file.
- JS, when necesary, should go in assets/scripts/script.css
- Whenever you create a new page, if any styling is shared with an existing page - extract the shared CSS out of the .html file and move it to the shared styles.css
