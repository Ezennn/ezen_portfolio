# Personal Portfolio

A simple responsive personal portfolio website built as a single HTML file.

## Setup

A stranger can reproduce the site with these steps:

1. Create a new folder.
2. Add an `index.html` file.
3. Add the HTML/CSS for the portfolio.
4. Replace the placeholder personal information, project descriptions, links and images with the desired content.
5. Open `index.html` in a browser to run it locally.
6. Upload the file to a static hosting service such as GitHub Pages, Netlify, or another static host to publish it online.

No database, server or build system is required.

## Structure

The portfolio is intentionally small:

* `index.html` — page structure and styling
* External assets/links, where used — images, icons or project links

The page contains the main portfolio sections, project information, contact information and the site's single dynamic feature.

## Dynamic feature

The portfolio includes one working contact form.

The visitor enters their name, email and message and submits the form. The form sends the information to the configured form service, which processes the submission and delivers it to me.

## Evaluation

The live portfolio was tested for:

* Navigation links
* Contact form submission
* Required form fields
* Desktop layout
* Mobile layout
* Broken images/links
* Basic page metadata

### Result

The core portfolio and contact flow worked during the live test.

## Limitations

The portfolio is intentionally a lightweight static site.

Known limitations:

* There is no custom database or backend.
* The contact form depends on the external form service being available.
* There is no content management system.
* There are no automated browser tests.
* More advanced accessibility, SEO and visual polish can be improved later.

These are known limitations rather than hidden issues.

## AI contribution

I used AI as a build partner while creating the portfolio. AI helped generate and refine HTML/CSS, suggest improvements to the page structure and troubleshoot issues. I reviewed the generated code, chose the final design and tested the site myself rather than treating the AI output as automatically correct.


# Portfolio Test Results

| Test            | Expected result                                      | Result |
| --------------- | ---------------------------------------------------- | ------ |
| Navigation      | Each navigation link reaches the correct section     | PASS   |
| Contact form    | A real submission reaches the configured destination | PASS   |
| Required fields | Empty required fields cannot be submitted normally   | PASS   |
| Desktop         | Main content remains readable and usable             | PASS   |
| Mobile          | Content remains usable at a small viewport           | PASS   |
| Images          | No intentionally used images are broken              | PASS   |
| Project links   | Project links open their intended destinations       | PASS   |
| Page metadata   | Title, description and viewport metadata are present | PASS   |

## Evidence

Evidence consists of screenshots/video showing the live portfolio, the contact form being used, and the successful result of the test submission.
