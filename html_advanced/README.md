# 0. Create your first webpage
Create your first HTML file `0-index.html` with:
- Add the doctype on the first line (without any comment)
- After the doctype, open and close a `html` tag
- Add the language tag, specify English for `ISO language code` and add the direction tag (ltr or rtl) on the `html` tag.
- Open your file in your browser (the page should be blank)

# 1. Structure your webpage
- Copy the content of `0-index.html` into `1-index.html`
- __Create the head and body sections__
    - inside the `html` tag, create the `head` and `body` tags (empty) in this order

# 2. The head - meta charset, viewport, title, description, favicons
- Copy the content of `1-index.html` into `2-index.html`
- Meta charset
- Viewport
- Title
- Description
- Favicons

# 3. Simple header, main, footer
- Copy the content of `2-index.html` into `3-index.html`
- Header
- Main
- Footer

# 4. Aside
- Copy the content of `3-index.html` into `4-index.html`
- change the `<title>` to put: `Article - Techium`
- inside the `main` tags
    - after the text, create the `aside` tags with text `Aside`

# 5. Section
- Copy the content of `3-index.html` into `5-index.html`
- inside your `<main>` section

# 6. Work, News, Testimonial articles
- Copy the content of `5-index.html` into `6-index.html`
- Work articles
- News articles
- Testimonials articles

# 7. Navigation
- Copy the content of `6-index.html` into `7-index.html`
- remove the `Header` text inside the `<header>`
- create the `nav` tag inside the `header` tag
    - it should remain empty for now

# 8. Level 1 headings
- Copy the content of `7-index.html` into `8-index.html`
- create the level 1 heading inside your `main` before your sections
    - put text `Homepage` in your heading tag

# 9. Level 2 headings
- Copy the content of `8-index.html` into `9-index.html`
- create mor heading

# 10. Level 3 headings
- Copy the content of `9-index.html` into `10-index.html`
- Services headings
- Works headings
- About Us headings
- Latest news headings

# 11. styleguide
- Copy the content of `3-index.html` into `11-index.html`
- change the title to `Styleguide - Techium`
- remove the text from `header`, `main`, and `footer`
- create a new `<section>` inside your `main` tag
    - create a `header` in this section
        - in the `header` add a level 2 heading with text `Headings`

# 12. Paragraphs
- Copy the content of `10-index.html` into `12-index.html`
- About Us paragraphs
- Latest news paragraphs
- Contact paragraph:
- Additional paragraphs:

# 13. styleguide paragraphs
- Copy the content of `11-styleguide.html` into `13-styleguide.html`
- After the existing section containing `Headings`, create a new `section` in `main`
    - in this section create a `header`
        - Inside the header, create a level 2 heading with text `Paragraph`
- after the `header` add a level 2 heading with text `Heading with a subtitle`
- after the level 2 heading, add a paragraph with text `This is my subtitle`
- after the last paragraph, add another paragraph with text: `Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.`

# 14. Span
- Copy the content of `12-index.html` into `14-index.html`
- In the very first `<header>`,
    - before the `nav`, create a `span` with the text `Techium`

# 15. Div
- Copy the content of `14-index.html` into `15-index.html`
- Wrap the contents of the `header` element with a `div`
- Wrap the content of each `section` element within a `div`
- Finally, wrap the contents of the `<footer>` tag with a `div`

# 16. Structure your sections
- Copy the content of `15-index.html` into `16-index.html`
- in the `div` in the Services `section`
    - create a `header` tag that wraps the `h2` and the `p`
    - create a `div` sibling to the `header` that wraps the rest of the content
- in the `div` in the Works `section`
    - create a header tag that wraps the `h2` and the `p`
    - create a `div` sibling to the `header` that wraps the rest of the content
- in the `div` in the About Us section
    - create a `header` tag that wraps the `h2` and the `p`
    - create a `div` sibling to the `header` that wraps the rest of the content
- in the `div` in the Latest news section
    - create a `header` tag that wraps the `h2`
    - create a `div` sibling to the `header` that wraps the rest of the content
- in the `div` in the Testimonials section
    - create a `header` tag that wraps the `h2` and the `p`
    - create a `div` sibling to the `header` that wraps the rest of the content
- in the `div` in the Contact section
    - create a `header` tag that wraps the `h2` and the first `p`
    - create a `div` sibling to the `header` that wraps the rest of the content

# 17. Comments
- Copy the content of `16-index.html` into `17-index.html`
- before the `header` add a line break and a comment saying `Header` to help with scanning your code
- before the `main` add a line break and a comment saying `Main` to help with scanning your code
- before the `footer` add a line break and a comment saying `Footer` to help with scanning your code
- before the `Hero section` add a line break and a comment saying `Hero section`
- before the `Services section` add a line break and a comment saying `Services section`
- before the `Works section` add a line break and a comment saying `Works section`
- before the `About Us` section add a line break and a comment saying `About Us section`
- before the `Latest news` section add a line break and a comment saying `Latest news section`
- before the `Testimonials section` add a line break and a comment saying `Testimonials section`
- before the `Contact section` add a line break and a comment saying `Contact section`

# 18. link your logo
- Copy the content of `17-index.html` into `18-index.html`
- in the `header`, wrap the `span` with a link that redirects to the page at the root of your folder (`/`)
- wrap the link with a `div`

# 19. Create new pages
Copy the content of `18-index.html` into `about.html`, `latest_news.html` and `contact.html`
- change the title of `about.html` to replace `Homepage` with `About`
- change the title of `latest_news.html` to replace `Homepage` with `Latest news`
- change the title of `contact.html` to replace `Homepage` with `Contact`

# 20. Add links
- Copy the content of `18-index.html` into `20-index.html`
- in your `nav` tags
    - create a link to `/` with the text `Home`
    - create an anchor to `services` with the text `Services`
    - create an anchor to `works` with the text `Works`
    - create an anchor to `about` with the text `About`
    - create an anchor to `latest_news` with the text `Latest news`
    - create an anchor to `testimonials` with the text `Testimonials`
    - create an anchor to `contact` with the text `Contact`

# 21. Add social media links
- Copy the content of `20-index.html` into `21-index.html`
- in the `div` in the `footer`
    - remove any text you have
    - create a link to `https://www.facebook.com/HolbertonSchool/` with the text Facebook
    - create a link to `https://twitter.com/holbertonschool` with the text Twitter
    - create a link to `https://www.instagram.com/holbertonschool/` with the text Instagram
