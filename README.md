# KNGS Computer Science Revision Hub

A collection of accessible, interactive revision resources for **Key Stage 3, GCSE and A Level Computer Science** at **Kings Norton Girls' School (KNGS)**.

The hub gives pupils a simple place to revisit classroom learning, practise key knowledge and build confidence before assessments. Resources are designed for independent study at home or in school.

## Features

- **Year-group navigation:** Find resources for Years 7, 8 and 9, alongside combined GCSE (Years 10 and 11) and A Level (Years 12 and 13) sections.
- **Interactive activities:** Flashcards, self-check questions and other tasks where appropriate.
- **Clear explanations:** Student-friendly notes, examples and visual memory aids.
- **Support and challenge:** Scaffolding to help pupils get started, plus extension activities to deepen understanding.
- **Assessment-focused revision:** Practice the knowledge and skills covered by each unit without reproducing the actual assessment questions or scenarios.
- **Mobile-friendly design:** Responsive pages designed to work on phones, tablets and computers.
- **Self-contained resources:** Individual revision pages can be used without installing extra software.

## Revision resources

The hub is organised by year group and unit. Available units may change as resources are added or updated.

| Year group | Revision areas |
| --- | --- |
| **Year 7** | Unit 1 and 2 revision, including foundational Computer Science knowledge and e-safety resources |
| **Year 8** | Unit 1 and 2 revision, plus further units including sorting and e-safety |
| **Year 9** | Computer Science units including Python programming, image editing and artificial intelligence |
| **GCSE (Years 10 and 11)** | OCR J277 [Unit 3: Networks](gcse/unit3.html) and [Unit 4: Network Security & Systems Software](gcse/unit4.html), including interactive simulations, flashcards, knowledge maps, revision notes and MCQs |
| **A Level (Years 12 and 13)** | One combined OCR H446 revision section, with resources coming soon |

**Open the site's home page (`index.html`) to see the current list of resources.** The home page is the authoritative directory of published units.


### GCSE Unit 4: Network Security & Systems Software

Open: https://kingsnortongirls.github.io/revision/gcse/unit4.html

Based on four lesson presentations (Network Threats, Preventing Vulnerabilities, Operating Systems and Utility Software), this standalone HTML revision page provides 41 core concepts, 53 flashcards, 48 original self-marking MCQs, a topic-linked knowledge map and eight interactive practice labs:

- Identify malware and attacks from short incident scenarios
- Audit a simulated phishing message
- Apply simplified firewall packet-filtering rules
- Step through a round-robin CPU scheduler
- Allocate and release RAM in a model operating system
- Reorganise fragmented files on an illustrative magnetic hard disk
- Compare indicative compression savings for different data types
- Encode and decode a message using a **demonstration-only** Caesar cipher

Simulations are educational models rather than production security tools. The source presentations underpin the topics; questions and scenarios are newly written, not copied from assessment papers. No login, external scripts or third-party APIs are required.

## How pupils can use the hub

1. Open the Revision Hub home page using the link provided by your teacher.
2. Choose your **year group** and **unit**.
3. Read the explanations and work through the examples.
4. Try the flashcards, quizzes and interactive tasks. Test yourself *before* checking an answer.
5. Use the support prompts if you are stuck, or try a challenge task if you are confident.
6. Return to topics you found difficult. Short, repeated revision sessions are more useful than simply rereading everything once.

**Tip:** Explain an answer aloud or write it down from memory before revealing it. This is a good way to check what you can genuinely recall.

## Device compatibility

The resources are intended to work in modern browsers, including **Safari on iPhone and iPad**, Chrome and Edge.

To keep flashcards usable on iPhones, especially when an HTML file is opened from the **Files** app:

- Questions and answers should remain readable without relying on 3D flip animations.
- Essential revision content should still be visible if JavaScript is unavailable or restricted.
- Buttons and other controls should be large enough to tap comfortably.
- Pages should adapt to smaller screens without horizontal scrolling.
- Images, notes and activities should be embedded or locally available where practical, rather than depending on third-party assets.

For the most consistent experience, **open the published GitHub Pages version in Safari**.

## Project structure

The precise file names may vary, but a typical layout is:

```text
revision-hub/
├── index.html             # Main revision hub / unit directory
├── y7/                    # Year 7 revision pages
│   └── ...
├── y8/                    # Year 8 revision pages
│   └── ...
├── y9/                    # Year 9 revision pages
│   └── ...
└── README.md              # This guide
```

The resources are primarily **standalone HTML files**, so they can be linked to directly and maintained unit by unit. Check the repository for its actual folder and file names.

## Adding or updating a revision unit

1. Create or update the unit's HTML file in the appropriate year-group folder.
2. Match the school's scheme of work, revision checklist and assessed skills.
3. Write **new** practice questions and examples. Do **not** copy questions, scenarios, data sets or numerical values directly from a live assessment.
4. Include clear explanations, useful keywords, support prompts, challenge tasks and opportunities for active recall.
5. Make interactive activities keyboard-accessible where possible and ensure that their core content is available as a readable fallback.
6. Test the page on desktop and mobile, including Safari on iPhone.
7. Add the new page to the links in `index.html`.
8. Commit the changes and check the published GitHub Pages site.

## Publishing with GitHub Pages

The site can be hosted as a static website using **GitHub Pages**. No database or server-side application is required for the standalone pages.

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the publishing branch (often `main`) and folder (usually `/ (root)`).
4. Save, then use the site URL shown by GitHub once the deployment succeeds.
5. Check that `index.html` loads and that all year-group links work.

If the repository is published from its root, a page in `y8/` is typically reached at `https://<username>.github.io/<repository>/y8/<filename>.html`.

## Quality and safeguarding principles

- Use **UK English**, clear language and accessible layouts suitable for secondary-school pupils.
- Keep practice aligned with the curriculum while protecting the integrity of school assessments.
- Avoid placing pupil names, marks, passwords or other personal information in public repository files.
- Prefer tools that work without accounts, sign-ins or tracking.
- Review links, accessibility and content accuracy when units or assessments change.

## About

Created for pupils studying **Computer Science at Kings Norton Girls' School**.

This is a school revision resource, not an official examination-board publication. Pupils should follow their teacher's guidance on which topics to revise for a particular assessment.
