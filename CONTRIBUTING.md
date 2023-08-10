# Contributing to Gov UI

Welcome to Gov UI! We're glad you're interested in contributing. Here are some guidelines to help you get started.

## Ways to Contribute

You can contribute to Gov UI in various ways:

- Reporting bugs
- Submitting feature requests
- Writing code
- Updating documentation
- Improving existing features
- Reviewing pull requests

## Prerequisites

Before you start contributing, make sure you have the following:

- Node.js 18 (LTS)
- Yarn

## Getting Started

To set up Gov UI locally and start contributing, follow these steps:

1. Fork the repository.

2. Clone the repository to your local machine, add upstream remote, Synchronize your `local master` branch from upstream.

```bash
    git clone https://github.com/<your_username>/govui.git
    cd govui

    git remote add upstream https://github.com/allancolibao/govui.git

    git checkout master
    git pull upstream master
```
3. Install all the dependencies with yarn.

```bash
    yarn install
```

4. Create branch

```bash
    git checkout -b example-branch
```

5. Make changes, commit and push to your fork repository.

```bash
    git push -u origin HEAD
```

6. Lastly, Go to the repository and make a Pull Request.🎉

## Code Guidelines

We value consistency and readability in our codebase. Please adhere to the following guidelines:

- Format code using `yarn prettier`

## Submitting Changes

When you're ready to submit your contribution:

1. Fork the repository and create a new branch for your feature/bugfix.
2. Make your changes and commit them with a descriptive message.
3. Push your branch to your forked repository.
4. Create a pull request (PR) to the main repository's `main` branch.
5. Ensure your PR description includes the context and purpose of your changes.

## Testing

Before submitting your changes, ensure that:

- All existing tests pass.
- You've added new tests to cover your changes.
- Your changes do not break existing functionality.

```bash
    yarn test
```

## Documentation

Clear and concise documentation is crucial. If you're introducing new features or making significant changes, update the documentation accordingly.

## Community Guidelines

Please review and adhere to our [Code of Conduct](https://github.com/allancolibao/govui/blob/main/CODE_OF_CONDUCT.md). We expect respectful and inclusive behavior from all contributors.

## Contact

If you have any questions or need assistance, feel free to reach out to [Allan Colibao](https://arcdev.me) at [colibaoallanreyes@gmail.com](mailto:colibaoallanreyes@gmail.com).

## License

By contributing to Gov UI, you agree that your contributions will be licensed under [MIT License](https://github.com/allancolibao/govui/blob/main/LICENSE).

We appreciate your contributions to Gov UI!
