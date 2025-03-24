# CLAUDE.md - Coding Guidelines for Website Project

## Development Commands
- **Run local server**: `python -m http.server` or `npx serve`
- **Validate HTML**: `npx html-validate index.html`
- **Format HTML/CSS/JS**: `npx prettier --write "**/*.{html,css,js}"`

## Code Style Guidelines
- **HTML**: Use Bulma CSS framework, indent with 4 spaces, use semantic tags
- **CSS**: Keep styles in `<style>` blocks within HTML, follow class naming from Bulma
- **JavaScript**: Use vanilla JS or jQuery for simple interactions
- **Conventions**:
  - Indent with 4 spaces consistently
  - Use classes for styling, ID for JS interactions
  - Keep markup semantic and accessible (use alt text for images)
  - Follow Bulma component patterns and class naming
  - Keep inline styles minimal, prefer class-based styling
  - Use descriptive variable/function names (camelCase)
  - Handle errors gracefully in JS with try/catch

## Notes
- Static site with no build process or backend
- Mobile-responsive design using Bulma classes
- No linting setup - use Prettier for formatting