# Contributing to flexoki-lualine.nvim

flexoki-lualine.nvim is an opinionated personal project designed to meet my aesthetic preferences.

While contributions may be considered, please note:

- This project reflects personal taste and design preferences
- There is no guarantee that contributions will be accepted
- Color choices and styling decisions are driven by my aesthetic vision
- The project may not follow conventional open source practices

If you find flexoki-lualine.nvim useful, you're welcome to:

- Fork it for your own needs
- Report bugs via GitHub issues
- Share ideas, though implementation is at maintainer's discretion

## Development Standards

### Commit Messages

This project follows the [Conventional Commits](https://www.conventionalcommits.org/) specification for commit messages.

#### Format

```
type[(optional scope)]: description

[optional body]

[optional footer(s)]
```

#### Types

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that do not affect the meaning of the code
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **test**: Adding missing tests or correcting existing tests
- **chore**: Changes to the build process or auxiliary tools

#### Examples

```
feat: add support for terminal mode colors

fix: correct inactive window color contrast

docs: add integration examples to README

feat(theme): enhance visual mode highlighting

fix!: update color references for flexoki.nvim v2.0

BREAKING CHANGE: requires flexoki.nvim v2.0 or higher
```

### Theme Development

When working on the lualine theme:

- Follow lualine's theme structure conventions
- Ensure colors reference flexoki.nvim's color palette
- Test with both light and dark backgrounds
- Maintain accessibility and contrast standards
- Verify all mode states are properly styled

Thank you for your understanding.
