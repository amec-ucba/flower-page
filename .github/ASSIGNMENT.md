# 📄 Flower Page

Lay out a multi-page website with HTML boxes and CSS: a wrapper, a header, a navigation
bar, a two-column main area, and a footer.

## 🎯 Overview

In this coding exercise, you will turn **The Flower Page** home page into a complete page
layout. First you will plan the page as a set of boxes. Then you will add those boxes to the
HTML with semantic layout elements: `header`, `nav`, `main`, `section`, and `footer`, all
inside a wrapper `div`. Finally, you will style each box in `main.css`, working from the
outside in. You'll start with the body and wrapper, then style the header, the navigation
bar, the main area and its two columns, and the footer.

The Cactus, Iris, and Ground Cover pages already have this box structure in their HTML.
They link the same `main.css` as the home page, so the styles you write for the home page
lay out the whole site at once.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Plan a page layout as a set of boxes before you write any code
- Use the semantic layout elements `header`, `nav`, `main`, `section`, and `footer`
- Group a page's content in a wrapper `div` and center it on the page
- Link a reset stylesheet and your own stylesheet, in the correct order
- Style a header and turn a list of links into a horizontal navigation bar
- Divide the main content area into left and right columns using classes
- Style a footer and keep it below the columns
- Use one shared stylesheet to style every page of a website

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. Watch
them **in order** and follow along in Visual Studio Code. Pause whenever you need time to
finish a step. It's normal to pause, rewind, and rewatch parts of a coding demonstration.

Each video builds on the previous one, so please don't skip ahead.

| Video | What you will do |
| --- | --- |
| **Introduction & Overview** | Tour the starter files and preview the finished page layout you are going to build. |
| **Part 1 — Page Box Structure** | Plan the page as a set of boxes (wrapper, header, nav, main, left and right columns, and footer) and see how they nest inside each other. |
| **Part 2 — Adding the HTML Boxes** | Add the wrapper `div`, `header`, `nav`, `main`, `section`, and `footer` elements to `index.html`, and link `reset.css` and `main.css`. |
| **Part 3 — Styling the Body & Wrapper** | Style the `body`, then give the wrapper a width and center it on the page. |
| **Part 4 — Header** | Style the header box that holds the site title. |
| **Part 5 — Navigation Bar** | Turn the list of links into a horizontal navigation bar. |
| **Part 6 — Main & Sections** | Style the `main` element and the `section` boxes inside it. |
| **Part 7 — Left & Right Columns** | Use the `left-column` and `right-column` classes to place the two sections side by side. |
| **Part 8 — Footer** | Style the footer and make sure it sits below both columns. |

> [!IMPORTANT]
> **A few steps in this repo are different from Canvas and the videos.** Follow the videos
> for the HTML and CSS, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files:** don't download `flowers start.zip`. Create your own repo
>   from this template and clone it in WebStorm, as described in the
>   [Getting Started guide](GETTING_STARTED.md).
> - **Branch:** do your work on a `develop` branch, not `main`. Before you commit, the
>   branch name at the top left of WebStorm should say `develop`, not `main`.
> - **Submitting:** don't zip your folder or upload a file. Publish your site to GitHub
>   Pages, open a pull request into `main`, and submit the **pull request URL** in Canvas,
>   not your repository URL. The [Submitting guide](SUBMITTING.md) has the
>   steps.

> [!IMPORTANT]
> Open the entire project **folder** in VS Code, not a single HTML file. Your pages need
> to find the CSS files and the `images` folder, so don't move or rename any starter files.

## 📂 Starter Files

| File / Folder | Purpose |
| --- | --- |
| `index.html` | The home page. It has the content but no layout boxes yet. You will add the wrapper, `header`, `nav`, `main`, `section`, and `footer` elements here, and link the stylesheets. |
| `cactus.html` | The Cactus page. Its box structure is already in place. Use it as a reference. |
| `iris.html` | The Iris page. Its box structure is already in place. |
| `groundcover.html` | The Ground Cover page. Its box structure is already in place. |
| `main.css` | Your stylesheet. It starts empty. Every page links it, so your styles apply to the whole site. |
| `reset.css` | Removes browser default styles so every page starts from the same blank slate. Don't edit it. |
| `images/` | Flower photos and the background images for the page and header. |

Link `reset.css` **before** `main.css`, the same way the other pages do, so your styles
build on top of the reset.

## ✅ Before You Submit

Check the following:

- [ ] `index.html` links `reset.css` and then `main.css`, and your styles show up in the browser
- [ ] All of the page content in `index.html` is inside a wrapper `div` with the class `wrapper`
- [ ] The site title is inside a `header`, and the list of links is inside a `nav`
- [ ] The main content is inside a `main` element, split into `section` elements with the classes `left-column` and `right-column`
- [ ] The copyright line is inside a `footer`
- [ ] The wrapper has a set width and is centered on the page
- [ ] The header and the navigation bar are styled, and the nav links run across the page horizontally
- [ ] The left and right columns sit side by side
- [ ] The footer sits below both columns
- [ ] The Home, Cactus, Iris, and Ground Cover links all work and every page uses the same layout
- [ ] Every image appears in the browser and has useful `alt` text
- [ ] You saved your files
- [ ] The site is live on GitHub Pages and the URL is in your pull request

## 🧮 Grading Rubric

| Criteria | Full credit | Points |
| --- | --- | --- |
| **HTML layout boxes** | `index.html` links `reset.css` and then `main.css`. The content is wrapped in a `div.wrapper` with a `header`, `nav`, `main` (with `left-column` and `right-column` sections), and `footer`. The markup is properly nested and closed. | 3 |
| **Body and wrapper** | The `body` is styled, and the wrapper has a set width and is centered on the page. | 2 |
| **Header** | The header box is styled and clearly separated from the rest of the page. | 2 |
| **Navigation bar** | The nav links display horizontally as a styled navigation bar, and every link goes to the right page. | 2 |
| **Main and sections** | The `main` element and its `section` boxes are styled with spacing that keeps the content readable. | 2 |
| **Left and right columns** | The `left-column` and `right-column` sections sit side by side using class selectors. | 2 |
| **Footer** | The footer is styled and sits below both columns. | 1 |
| **Publishing and submission** | The site is live on GitHub Pages. The pull request from `develop` into `main` is open, its template is filled in, and its URL is submitted in Canvas. | 1 |
| **Total** |  | **15** |

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save the file in VS Code?
- Are `reset.css` and `main.css` linked in the `head` of `index.html`, in that order?
- Do the class names in your HTML match the class selectors in your CSS, including the `.`?
- Did you close every box element (`</div>`, `</header>`, `</nav>`, `</main>`, `</section>`, `</footer>`) in the right place?
- Are your image paths written as `images/file-name.jpg`, including the folder name?
- Is the footer jumping up beside the columns? Check that it is outside `main` and starts below the columns.
- Do the other pages look right? They share `main.css`, so check your home page styles first.
- Did you commit **and** push your changes in WebStorm?

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [MDN — Document and website structure](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents)
- [MDN — The box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)
- [MDN — Styling links](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Styling_links)
- [MDN — Class selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input): paste your
  HTML in to catch unclosed tags
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input):
  paste your CSS in to catch typos and missing semicolons

---

The AI policy and submission instructions are in the [README](../README.md).
