# Graduate Advice Hub

A comprehensive directory and advice resource platform for graduate students, built with Jekyll and hosted on GitHub Pages.

## 🎓 About

Graduate Advice Hub is a community-driven project designed to support graduate students throughout their academic journey. The platform provides:

- **Practical Advice**: Guidance on various aspects of graduate life, from choosing an advisor to managing research and balancing work-life commitments
- **Resource Directory**: Curated collection of tools, websites, books, and materials to help graduate students succeed
- **Community Knowledge**: Insights and tips from current graduate students and recent graduates

## 🚀 Getting Started

### Prerequisites

- Ruby 3.0 or higher
- Bundler

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/stogiannidis/grad-advice-hub.git
   cd grad-advice-hub
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and visit `http://localhost:4000/grad-advice-hub/`

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## 📝 Contributing

We welcome contributions from the community! Here's how you can help:

### Adding Advice Content

1. Create a new Markdown file in the `_advice` directory
2. Add front matter with title and category:
   ```yaml
   ---
   layout: page
   title: Your Advice Title
   category: Category Name
   ---
   ```
3. Write your advice content in Markdown

### Adding Resources

1. Create a new Markdown file in the `_resources` directory
2. Add front matter with title and category:
   ```yaml
   ---
   layout: page
   title: Resource Name
   category: Resource Category
   ---
   ```
3. Describe the resource with relevant details

### Submitting Changes

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes and commit them
4. Push to your fork and submit a pull request

## 🏗️ Project Structure

```
grad-advice-hub/
├── _advice/              # Advice articles
├── _resources/           # Resource pages
├── _config.yml           # Jekyll configuration
├── index.md              # Homepage
├── advice.md             # Advice index page
├── resources.md          # Resources index page
├── about.md              # About page
└── Gemfile               # Ruby dependencies
```

## 🛠️ Built With

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [Minima](https://github.com/jekyll/minima) - Jekyll theme
- [GitHub Pages](https://pages.github.com/) - Hosting platform

## 📄 License

This project is open source and available for anyone to use and contribute to.

## 🤝 Community

- Report bugs or request features by [opening an issue](https://github.com/stogiannidis/grad-advice-hub/issues)
- Join discussions and share ideas
- Help improve documentation

## 📬 Contact

For questions or suggestions, please open an issue on GitHub.

---

*Making the graduate journey a little bit easier, one resource at a time.*