Prism Lab — Gradient Card Portfolio


A vibrant, card‑based one‑page portfolio for generative art and creative coding experiments. The layout uses a scroll‑snap vertical flow, glowing gradients and compact “work cards” to present small interactive studies.​

Features
Three main screens: hero intro, “Selected cards” gallery, and collaborations/contact.​

Vertical scroll‑snap sections for a slide‑like navigation experience.​

Card‑based work grid with four project tiles and image hovers.​

Gradient background with dark content panels to keep typography readable.​

Fully responsive: grid collapses to one column and scroll‑snap is disabled on small screens for better usability.​

Tech stack
HTML5 single‑page structure with semantic sections (section, header, article).​

Modern CSS: scroll‑snap, flexbox, CSS grid, gradients, and card hover effects.​

Vanilla JavaScript: only for smooth scrolling buttons that jump between sections.​

Getting started
Clone or download the repository.​

bash
git clone https://github.com/your-username/prism-lab-cards.git
cd prism-lab-cards
Open index.html directly in a browser, or use the Live Server extension in VS Code for auto‑reload.​

No build tools are required; this is a static HTML/CSS/JS project.​

Customization
Branding:

Update the name “Prism Lab”, tagline and nav labels in the hero <header> and hero copy.​

Selected cards:

Edit titles, meta labels and descriptions inside each .work-card in the #work section.

Replace the Unsplash image URLs in each background-image with your own artwork or screenshots.​

Collaborations:

Adjust collaboration text, project types and contact info in the #contact section to match your studio.​

Visual style:

Tweak gradients, colors and corner radiuses in the root CSS variables and card styles at the top of the file.​

Deployment
GitHub Pages: push the repo, then in Settings → Pages choose “Deploy from a branch”, select main and the root folder.​

Static hosting (Netlify, Vercel, etc.): drag‑and‑drop the project folder or connect the GitHub repo; no special config is needed.
