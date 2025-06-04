# Contributing to Frostgate

Hello there! First off, thank you for considering contributing to Frostgate! It's people like you that make Frostgate such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* Use a clear and descriptive title
* Describe the exact steps which reproduce the problem
* Provide specific examples to demonstrate the steps
* Describe the behavior you observed after following the steps
* Explain which behavior you expected to see instead and why
* Include any error messages or logs

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* A clear and descriptive title
* A step-by-step description of the suggested enhancement
* Any possible drawbacks
* Why this enhancement would be useful to most Frostgate users

### Pull Requests

* Fill in the required template
* Do not include issue numbers in the PR title
* Include screenshots and animated GIFs in your pull request whenever possible
* Follow the Rust styleguide
* Include thoughtfully-worded, well-structured tests
* Document new code
* End all files with a newline

## Development Process

1. Fork the repo
2. Create a new branch from `main`
3. Make your changes
4. Run the tests
5. Push to your fork and submit a pull request

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

### Rust Style Guide

* Run `cargo fmt` before committing
* Follow the [Rust API Guidelines](https://rust-lang.github.io/api-guidelines/)
* Document all public APIs
* Use meaningful variable names
* Keep functions focused and small

### Testing

* Write tests for all new code
* Ensure all tests pass locally before submitting
* Include both unit tests and integration tests where appropriate
* Use meaningful test names that describe what is being tested

### Documentation

* Update documentation with any changes
* Use clear and consistent terminology
* Include examples where helpful
* Keep READMEs up to date

## Project Structure

```
frostgate/
├── frostgate-circuits/   # ZK circuit implementations
├── frostgate-icap/       # Chain abstraction protocol
├── frostgate-zkip/       # ZK backend interface
├── frostgate-prover/     # Proof generation
├── frostgate-verifier/   # Proof verification
├── frostgate-relayer/    # Message relaying
├── frostgate-node/       # Full node implementation
└── frost-cli/            # CLI tools
```

## Getting Help

* Join our [Discord](https://discord.gg/frostgate)
* Check out the [documentation](https://github.com/frostgate/frostgate-docs/)
* Ask in GitHub Issues

## Review Process

The core team reviews Pull Requests on a regular basis. After feedback has been given we expect responses within two weeks. After two weeks we may close the pull request if it isn't showing any activity.

### Review Checklist

- [ ] Code follows style guidelines
- [ ] Tests are passing
- [ ] Documentation is updated
- [ ] Commit messages are clear
- [ ] Changes are appropriate and aligned with project goals

## Community

* Join our [Discord](https://discord.gg/frostgate)
* Follow us on [Twitter](https://twitter.com/devfrostgate)
* Read our [blog](https://medium.com/@frostgate)

## Recognition

Contributors who make significant improvements will be recognized in our:

* Release notes
* Contributors list
* Social media shoutouts

Thank you for contributing to Frostgate! 