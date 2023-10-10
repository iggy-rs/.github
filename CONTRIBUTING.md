Hello!

At first, thank you for your interest in contributing to [Iggy.rs](https://iggy.rs)! We're happy to welcome you to the community.

To begin with, feel free to take a look at the list of open issues in the specific repository, whether you're interested in contributing to the core server written in Rust, a particular SDK implemented in a specific language or the Web UI.

For example, you can find the list of open issues for the core Iggy.rs streaming server [here](https://github.com/iggy-rs/iggy/issues). You can filter the issues by labels, e.g. you can find the list of issues marked as [good first issue](https://github.com/iggy-rs/iggy/issues?q=is:issue+is:open+label:%22good+first+issue%22) if you're just starting with Iggy.rs.

If you don't find any issue that you'd like to work on, **feel free to create a new one**. Please, make sure to include the detailed description in the issue, so that other contributors can understand what is the required functionality and how to test it. If it's a bug report, please include the steps to reproduce the bug. Also, keep in mind to attach the appropriate labels to the issue.

## Pull requests

If you're working on an issue, please **assign yourself** to it, so that other contributors know that you're working on it. If you're not sure how to implement the functionality, feel free to ask for help in the comments below the issue and on our [Discord](https://iggy.rs/discord) server.

In general, the workflow for contributing to the project is as follows:

1. Fork the repository
2. Create a new branch with the name of the issue you're working on
3. Implement the functionality and tests if applicable
4. Run the tests for the whole solution (e.g. `cargo test` for the Iggy.rs server)
5. Run the specific formatter (e.g. `cargo fmt` for the Iggy.rs server) if applicable
6. Create a pull request to the `master` branch of the original repository
7. Include the detailed description of the changes in the PR
8. Wait for the CI to pass and for the code review

You might also find an additional, detailed PR guide for the specific repository like [this one](https://github.com/iggy-rs/iggy/blob/master/PULL_REQUEST_TEMPLATE.md).