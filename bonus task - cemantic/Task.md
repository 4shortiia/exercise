# Assignment: Semantic HTML Structure for "Luxury Stays" Portal

### Project Overview

Your task is to build the HTML skeleton for a premium hotel network's portal, "Luxury Stays." The page should function as a content hub that includes travel blogs, hotel services, and essential guest information.

The focus of this assignment is **Semantic HTML**—your code must describe the meaning of the content, not just its appearance.

---

### Technical Requirements & Structure

#### 1. Header & Global Navigation (`<header>`, `<nav>`)

- Define the site branding using an `<h1>` tag.
- Create a primary navigation bar inside a `<nav>` element.
- The navigation must contain a list (`<ul>`, `<li>`) with links to: Home, Rooms, Blog, FAQ, and Contact.
- Use **Anchor Links** (IDs) so that clicking a link jumps to the corresponding section on the page.

#### 2. Hero Section (`<section>`)

- Create a welcoming "Hero" area for the website.
- Include an `<h2>` heading and a descriptive paragraph about the hotel's philosophy.
- Add a "Call to Action" button (e.g., "Book Your Stay").

#### 3. Hotel Blog Section (`<main>`, `<article>`)

Inside the `<main>` area, create a section titled "Travel Insights" containing at least **3 blog posts**:

- Each post must be wrapped in an `<article>` tag.
- **Post Structure:**
  - `<header>`: The post title (`<h3>`) and metadata (Author using `<address>` and Date using `<time>`).
  - `<figure>` & `<figcaption>`: Include a placeholder for an image with a descriptive caption (e.g., "Panoramic view from our Penthouse Suite").
  - **Content:** At least two paragraphs (`<p>`) describing a travel destination or hotel tip.
  - `<footer>`: Include relevant hashtags or categories (e.g., #LuxuryTravel) and a "Read More" link.

#### 4. Services & Sidebar (`<aside>`)

- Use an `<aside>` element to list "Extra Services" (e.g., Spa & Wellness, Airport Transfer, Rooftop Pool).
- This content should be related to the main page but distinct from the blog posts.

#### 5. Interactive FAQ Section (`<section>`)

- Implement a Frequently Asked Questions block using `<details>` and `<summary>` tags.
- Include questions about:
  - Check-in/Check-out times.
  - Pet policy (Use `<strong>` to highlight specific restrictions).
  - Cancellation policy.

#### 6. Text Formatting & Inline Tags

- Include a famous travel quote using the `<blockquote>` tag.
- Use the `<mark>` tag to highlight a current special offer or discount.
- Use the `<code>` tag to display the technical format of the hotel's Wi-Fi password (e.g., `LS_Guest_2024`).

---

### Evaluation Criteria (Rubric)

| Criteria                  | Weight | Description                                                      |
| :------------------------ | :----- | :--------------------------------------------------------------- |
| **Semantic Accuracy**     | 40%    | Correct use of tags (e.g., article vs section, header vs div).   |
| **Information Hierarchy** | 20%    | Proper logical nesting of headings (h1 → h2 → h3).               |
| **Detailing**             | 20%    | Correct implementation of `<time>`, `<address>`, and `<figure>`. |
| **Navigation**            | 20%    | Fully functional internal navigation using IDs and Anchors.      |

---

### Submission Instructions

- **File Name:** `luxury-stay-project.html`
- **Formatting:** Ensure your code is properly indented for readability.
- **Comments:** Add HTML comments (``) to explain why you chose specific semantic tags for the Sidebar and the Blog posts.
