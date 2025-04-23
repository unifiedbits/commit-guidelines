# UnifiedBits Commit Message Guidelines

Welcome to the official commit convention guide for UnifiedBits!  
We follow the **Conventional Commits** specification to ensure clarity, traceability, and automation in our development process.

---

## 📌 Why Use Conventional Commits?

- 🧠 Clear project history
- 🚀 Easy changelog generation
- 🤖 Enables automation (versioning, deployments)
- 🤝 Improves team collaboration and onboarding

---

## 🛠️ Commit Message Format

A commit message must be structured as follows:

```
<type>(optional scope): <short summary>

[optional body]

[optional footer]
```

---

### ✅ Example

```
feat(auth): add login with OTP support

This introduces OTP-based authentication using Twilio.
Also updates the user model to include phone verification.

Fixes #24
```

---

## 🔤 Allowed Commit Types

| Type     | Description |
|----------|-------------|
| `feat`   | A new feature |
| `fix`    | A bug fix |
| `docs`   | Documentation only changes |
| `style`  | Code style changes (formatting, missing semicolons, etc.) |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `perf`   | Performance improvements |
| `test`   | Adding or updating tests |
| `chore`  | Maintenance tasks (configs, deps, CI/CD) |

---

## 🧩 Optional Scopes

Use **scopes** to specify which part of the codebase is affected.  
Example: `feat(api)`, `fix(ui)`, `docs(readme)`

| Scope Examples |
|----------------|
| `auth` |
| `ui` |
| `api` |
| `core` |
| `docs` |
| `deps` |

---

## 📋 Writing Good Commit Messages

- ✅ Use the **imperative mood**: "fix bug" not "fixed bug"
- ✅ Keep subject line under **72 characters**
- ✅ Use body to explain **why**, not just **what**
- ✅ Separate the **subject**, **body**, and **footer** with blank lines
- ✅ Reference issues or PRs in the footer (e.g., `Fixes #12`)

---

## 🔄 Sample Commit Examples

Here are realistic examples categorized by type:

### 🎯 `feat`: New Feature
```
feat(auth): add login with OTP support
feat(dashboard): implement user analytics charts
feat(api): add endpoint for bulk file processing
```

### 🐛 `fix`: Bug Fix
```
fix(ui): resolve button misalignment on mobile view
fix(api): correct 500 error on invalid input
fix(auth): prevent token from expiring prematurely
```

### 📄 `docs`: Documentation Changes
```
docs(readme): update installation instructions
docs(api): add usage examples to user routes
docs(contributing): explain branching strategy
```

### 🎨 `style`: Formatting & Styling
```
style(ui): unify font sizes across components
style(css): apply consistent padding and margins
style(auth): fix lint warnings and spacing issues
```

### ♻️ `refactor`: Code Refactoring
```
refactor(core): extract utility functions from controller
refactor(api): simplify query logic in search route
refactor(auth): remove unused middleware
```

### 🚀 `perf`: Performance Improvements
```
perf(api): optimize DB query for loading dashboard
perf(ui): lazy load images for faster initial load
```

### ✅ `test`: Adding/Updating Tests
```
test(api): add test cases for file upload
test(auth): increase test coverage for login flow
test(ui): snapshot tests for new components
```

### 🔧 `chore`: Maintenance/Meta
```
chore(ci): add GitHub Actions workflow for testing
chore(deps): upgrade dependencies to latest versions
chore(project): rename folders for clarity
```

---

## 🧪 Tools to Help

- 🛡️ **[Commitlint](https://github.com/conventional-changelog/commitlint)** – Lint commit messages
- 🤖 **[Commitizen](https://github.com/commitizen/cz-cli)** – Generate commits via CLI prompts
- 📦 **[Semantic Release](https://semantic-release.gitbook.io/)** – Automate changelog and versioning

---

## 📚 Resources

- 📘 [Conventional Commits](https://www.conventionalcommits.org/)
- 🤩 [Gitmoji (Optional)](https://gitmoji.dev)

---

## 🔮 Final Note

Following a convention for commit messages ensures every contributor understands the codebase history clearly, automates release processes, and scales the team with confidence.

> “Quality is never an accident; it is always the result of intelligent effort.” – John Ruskin

Happy committing! 🚀  
— Team **UnifiedBits**
