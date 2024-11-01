# Contributing to RedArc

Thank you for your interest in contributing to **RedArc**! This guide outlines the practices and conventions we follow to ensure a smooth and collaborative development process.

## Etiquette for Contributions

### 1. Branch Naming Convention
- **New Branch for Each Change**: A new branch should be created for each change.
- **Branch Naming Format**: Follow this naming pattern: `<type>/<description>-<ticket number>`.
  - **type**: Describes the purpose of the change, such as `feat`, `fix`, `refactor`, or `chore`.
  - **description**: A brief description of the change in kebab-case.
  - **ticket number**: The associated ticket or issue number.

#### Example Branch Names:
- `fix/update-erroneous-tracking-algorithm-TR-001`
- `feat/add-initial-tracker-setup-TR-002`
- `chore/add-contributing-guide-TR-003`

### 2. Pull Requests
- **One Change per PR**: Each Pull Request (PR) should address a single change or increment, keeping PRs small and focused for easier review.
- **Incremental PRs for Each Issue/Ticket**: An issue or ticket may require multiple PRs, allowing changes to be reviewed in steps.
- **Squash and Merge**: PRs are to be squashed and merged into `main` to keep the commit history clean and concise.

### 3. Testing
- **Test Coverage**: Each PR should include tests to cover all relevant scenarios.
- **Testing Focus**: Tests should primarily focus on validating data manipulation within modules to ensure accurate functionality.

### 4. Commit Messages and PR Titles

We follow a consistent pattern for commit messages and PR titles:

#### Format
```
<type>(<component>): <description>
```
- **type**: Describes the purpose of the change:
  - `feat`: A new feature
  - `fix`: A bug fix
  - `refactor`: Code changes that do not introduce new features or fixes
  - `chore`: Minor updates or maintenance tasks (e.g., documentation)
- **component**: The part of the project affected (e.g., `tracker`, `docs`, `utils`).
- **description**: A brief explanation of the change.

#### Examples

- Acceptable **commit messages**:
  - `chore(docs): add CONTRIBUTING.md doc`
  - `feat(tracker): add initial tracking function`

- Acceptable **PR title**:
  - `Feat(tracker): Set up initial framework for tracking ball trajectory`

Thank you for helping make **RedArc** better! We appreciate your contributions and adherence to these guidelines.
