# Yugicchi's blog Repository

This is the main repository for the blog. It contains all files and folders for assets like stylesheets and posts.  

## Project Structure

```markdown
📁 yugicchi.github.io/
├── 📁 assets/
│   ├── 📁 css/
│   │   └── style.css
│   └── 📁 images/
├── 📁 content/
│   ├── 📁 posts/
│   ├── 📁 tags/
│   └── 📁 archive/
├── 📁 layouts/
├── 📁 includes/
├── index.html
└── README.md
```

---

## To-Do List

### Assets
- [ ] **CSS (`assets/css/style.css`)**: Create or update the main stylesheet. Define basic styles for fonts, colors, and layout.
- [ ] **Images (`assets/images`)**: Add any necessary images for initial posts or layout (e.g., logo, header image).

### Content
- **Posts (`content/posts`)**
  - [ ] **Create initial posts**: Write at least one post in Markdown format to ensure proper layout and styling.
  - [ ] **Organize posts by date**: Follow the format `YYYY-MM-DD-title.md` for consistent organization.
  - [ ] **Add front matter**: Include metadata (title, date, tags) at the top of each post.

- **Tags (`content/tags`)**
  - [ ] **Create tag files**: Add files for each category or topic (e.g., `storytelling.md`, `poem.md`).
  - [ ] **List associated posts**: Link each post to its corresponding tag page.

- **Archive (`content/archive`)**
  - [ ] **Set up archive by year**: Create a file for each year (e.g., `2023.md`, `2024.md`) to group posts by date.
  - [ ] **Link posts to archives**: Update each year's archive file to include links to that year's posts.

### Layouts
- **Base Layout (`layouts/base.html`)**
  - [ ] **Design base layout**: Create a foundational HTML structure for the blog.
  - [ ] **Add header and footer includes**: Integrate `header.html` and `footer.html` from the `includes` across pages.

- **Post Layout (`layouts/post.html`)**
  - [ ] **Design post layout**: Customize layout for individual blog posts, including title, content, tags, and navigation.
  
- **Tag Layout (`layouts/tag.html`)**
  - [ ] **Design tag page layout**: Set up a layout to display all posts under a specific tag.

### Includes
- **Header (`includes/header.html`)**
  - [ ] **Create header component**: Add navigation links to main pages (e.g., Home, About, Archive).
  - [ ] **Add blog title and logo**: Display the blog title or logo for branding.

- **Footer (`includes/footer.html`)**
  - [ ] **Create footer component**: Add links to social media, contact information, and copyright notice.
  - [ ] **Add back-to-top link**: Consider adding a link to scroll back to the top of the page.

### Homepage (`index.html`)
- [ ] **Set up homepage**: Write a welcome message or introduction for the blog.
- [ ] **List recent posts**: Include a list of the most recent posts for easy access.

### Documentation
- **README.md**
  - [x] **Project overview**: Provide an overview of the blog and repository structure.
  - [x] **To-do list**: Outline tasks needed to set up and maintain the blog.
  - [ ] **License**: 

---

## Future Enhancements
- [ ] Add JavaScript (`assets/js/script.js`): Implement any custom JavaScript needed for features like toggles, animations, or responsive behavior.
- [ ] Add pagination for posts.
- [ ] Implement search functionality for easy navigation.
- [ ] Improve mobile responsiveness and accessibility.

---

Happy Blogging!

### License
- **Code**: Licensed under the MIT License. Free for personal and commercial use with attribution.
- **Content**: Licensed under CC BY-NC 4.0. You may use, share, and adapt blog posts for personal and academic purposes with attribution. Commercial use is not permitted.
