# Commit Message Guidelines

Generate commit messages in the Conventional Commits format, incorporating Gitmoji for enhanced clarity. Follow this structure:

```
<type>[optional scope]: <gitmoji> <short description>

[mandatory body]
```

## Examples

- `feat(auth): :sparkles: add login validation`
- `fix(api): :bug: resolve data fetch timeout`
- `docs: :memo: update README installation`
- `style: :art: format code per linting rules`
- `refactor: :recycle: restructure platform detection`

## Commit Types

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes, including README updates, JSDoc comments, and code documentation
- **style**: Changes not affecting code functionality (formatting, whitespace, etc.)
- **refactor**: Code structure changes that neither fix bugs nor add features
- **perf**: Code changes that improve performance
- **test**: Adding or correcting tests
- **build**: Changes affecting the build system or dependencies
- **ci**: Changes to CI configuration, such as GitHub Actions or Jenkins
- **chore**: Other changes not modifying source or test files
- **revert**: Reverting a previous commit

## Guidelines

- **Subject Line**:
  - Limit to 50 characters.
  - Use the imperative mood (e.g., "Add", "Fix", "Update").
  - Capitalize the first letter.
  - Do not end with a period.
  - Always include a relevant Gitmoji code at the start of the description. Match the Gitmoji to the type of change.

- **Body**:
  - **Mandatory** for all commits.
  - Separate from the subject line with a blank line.
  - Wrap lines at 72 characters.
  - Use bullet points (`*`) for multiple items.
  - Explain **what** and **why** the change was made.
  - Include relevant context or technical details.

## Handling Large Changes

For commits involving extensive changes across multiple files or modules:

- Use a generic description to indicate a significant update.
- Example:
  - `chore: :package: massive upgrade across modules`

## Additional Resources

For a comprehensive list of Gitmoji codes and their meanings, refer to the [Gitmoji Guide](https://gitmoji.dev/).
