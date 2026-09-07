# Goroka Secondary School Website

A responsive website for Goroka Secondary School in Goroka, Eastern Highlands, Papua New Guinea.

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Navigation links to Home, About, Programmes, Information, and Contact sections
- Students image featured on the Home section
- Career Talk image featured in the Information section
- Assembly image used as the site background
- Black surfaces with bright yellow text
- Responsive timetable and contact form

## Project Structure

```text
.
├── index.html
├── about.html
├── programme.html
├── information.html
├── contact.html
├── style.css
└── Images/
    ├── Assembly.jpg
    ├── Career Talk.jpg
    └── Students.jpg
```

## Running the Website

Open `index.html` in a web browser.

For best results, serve the project with a local web server so that all image and stylesheet paths load correctly. For example, with Python installed:

```bash
python -m http.server
```

Then visit `http://localhost:8000` in your browser.

## Contact Form

The contact form currently submits to `submit_form.php`. A PHP backend must be added and configured before form submissions can be processed.


## AI Use Declaration

I declare that Generative AI was utilized in the development of this website project [index: 0.1.2].

* **Tools Used:** Copilot, Gemini, and GitHub Copilot
* **Extent of Assistance:** Assisted in structuring the 5-page layout, setting up semantic HTML5 tags, and configuring the basic CSS styling for the dark/yellow color theme.
* **Human Verification:** All AI-suggested code was thoroughly reviewed, modified to meet assessment constraints, manually validated, and tested locally [index: 0.1.1, 0.1.2]. I take full academic responsibility for the final codebase [index: 0.1.2].
