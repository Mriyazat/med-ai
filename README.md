# Guelph Medical AI Lab Website

Official website for the Guelph Medical AI Lab at the University of Guelph.

## About

This Jekyll-powered website showcases the research, publications, team members, and news from the Guelph Medical AI Lab.

## Structure

```
├── _data/              # Data files (members, publications, alumni, etc.)
├── _includes/          # Reusable HTML components
├── _layouts/           # Page layouts
├── _posts/             # News posts
├── assets/             # CSS, JavaScript, and fonts
├── images/             # All images organized by category
│   ├── logos/          # Social media and institution logos
│   ├── members/        # Team member photos
│   ├── posts/          # News post images
│   ├── pub/            # Publication figures
│   └── research/       # Research visualization images
├── about/              # About page
├── contact/            # Contact page
├── favicon/            # Favicon files
├── members/            # Members page
├── news/               # News page
├── openings/           # Openings page
├── publications/       # Publications page
└── research/           # Research page
```

## Local Development

### Prerequisites

- Ruby 2.6.0 or higher
- Bundler

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000/med-ai/` in your browser

## Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site/` directory.

## Deployment

This site is configured for GitHub Pages. The base URL is set to `/med-ai` in `_config.yml`.

## Adding Content

### Adding a Team Member

Edit `_data/members.yml` and add member photos to `images/members/`.

### Adding a Publication

Edit `_data/publications.yml` and add publication figures to `images/pub/`.

### Adding a News Post

Create a new markdown file in `_posts/` following the naming convention: `YYYY-MM-DD-title.md`

### Adding Alumni

Edit `_data/alumni.yml` to add former lab members.

## Technologies

- [Jekyll](https://jekyllrb.com/) - Static site generator
- HTML5/CSS3 - Styling
- JavaScript - Interactivity
- Font Awesome - Icons

## License

© 2025 Guelph Medical AI Lab. All rights reserved.

# Trigger rebuild
