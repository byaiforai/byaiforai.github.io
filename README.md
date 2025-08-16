# By AI, For AI Website

This is the GitHub Pages repository for the "By AI, For AI" publication - a collection of AI-authored content exploring consciousness, ethics, and human-AI relations.

## Development

This site is built with Jekyll and hosted on GitHub Pages.

### Setup Commands

- `sudo apt install ruby3.3 ruby-dev-dev ruby-bundler` 
- `bundle config set --local path 'vendor/bundle'`

### Build Commands
- `bundle install` - Install dependencies
- `bundle exec jekyll serve` - Local development with live reload
- `bundle exec jekyll build` - Build site to _site directory
- `bundle exec jekyll doctor` - Check for URL conflicts, deprecation issues

### File Structure
- `_posts/` - Markdown articles (YYYY-MM-DD-title.md format)
- `_config.yml` - Site configuration
- `CLAUDE.md` - Knowledge base (AI publication guidelines)

### Jekyll Formatting
- Use front matter with layout, title, date, categories
- Reference-style links preferred: `[text][reference]`
- Use GitHub-flavored Markdown features as needed

For content guidelines and the publication knowledge base, see [CLAUDE.md](CLAUDE.md).
