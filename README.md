# Academic Website Template

This is a clean Jekyll-based academic website template. Originally created by Martin Saveski.

## Setup Guide

1. **Install Jekyll** (if not already installed):
   ```bash
   gem install jekyll bundler
   ```

2. **Test locally**:
   ```bash
   jekyll serve
   ```
   Then visit `http://localhost:4000` in your browser.

3. **Deploy to GitHub Pages** (recommended):
   - Push this repository to GitHub
   - Enable GitHub Pages in repository settings
   - Your site will be available at `https://[YOUR_GITHUB_USERNAME].github.io/[REPOSITORY_NAME]`

## Files to Edit

### Essential Files to Customize:

1. **`_data/main_info.yaml`** - Your basic information
   - Name, title, email
   - Social media links
   - Profile picture path

2. **`index.html`** - Main page content
   - Bio section
   - Research interests
   - Any additional sections

3. **`_data/publications.yaml`** - Your publications
   - Add your papers, conference proceedings, etc.
   - Mark selected papers with `selected: y`

4. **`_data/experience.yaml`** - Your timeline/CV
   - Education history
   - Work experience
   - Internships

5. **`_data/projects.yaml`** - Research projects (optional)
   - Project titles and descriptions
   - Thumbnail images
   - Links to project pages

6. **`_config.yml`** - Site configuration
   - Update the `baseurl` to match your GitHub username or custom domain

7. **`_layouts/default.html`** - Site metadata
   - Update meta tags for SEO
   - Modify navigation if needed

### Asset Folders:

- **`assets/profile-pics/`** - Add your profile photo here
- **`assets/cv/`** - Add your CV as `cv_web.pdf`
- **`assets/publications/`** - Store publication PDFs and slides
- **`assets/projects/`** - Store project images and files

## External Libraries

- Framework: [Jekyll](http://jekyllrb.com/)
- CSS: [Skeleton](http://getskeleton.com)
- Icons: [Font Awesome](http://fontawesome.io/)
- Academic Icons: [Academicons](https://jpswalsh.github.io/academicons/)