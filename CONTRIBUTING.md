# Contributing Guidelines

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional
documentation, we greatly value feedback and contributions from our community.

Please read through this document before submitting any issues or pull requests to ensure we have all the necessary
information to effectively respond to your bug report or contribution.

## Reporting Bugs/Feature Requests

We welcome you to use the GitHub issue tracker to report bugs or suggest features.

When filing an issue, please check existing open, or recently closed, issues to make sure somebody else hasn't already
reported the issue. Please try to include as much information as you can. Details like these are incredibly useful:

* A reproducible test case or series of steps
* The version of our code being used
* Any modifications you've made relevant to the bug
* Anything unusual about your environment or deployment

## Contributing via Pull Requests

Contributions via pull requests are much appreciated. Before sending us a pull request, please ensure that:

1. You are working against the latest source on the *main* branch.
2. You check existing open, and recently merged, pull requests to make sure someone else hasn't addressed the problem already.
3. You open an issue to discuss any significant work - we would hate for your time to be wasted. For instance, if you want to propose a new MCP Server, you would need to first open a RFC issue.

The [Developer guide](DEVELOPER_GUIDE.md) provides the steps to set up your dev environment and make sure your code is ready before you submit your pull request.

### Required Contributor Statement

**IMPORTANT**: All pull requests must include the following contributor statement in the PR description:

```
By submitting this pull request, I confirm that you can use, modify, copy, and redistribute this contribution, under the terms of the [project license](https://github.com/awslabs/mcp/blob/main/LICENSE).
```

This statement is automatically included in the pull request template and is required by our pull-request-lint workflow. If your PR description is missing this statement, the automated checks will fail. This confirms that your contribution is made under the terms of the Apache 2.0 license.

### Special `./README.md` considerations for new MCP servers

When adding a new MCP server, you must update the README.md to include your server in the appropriate categories under "Available MCP Servers". Add it to both the "Browse by What You're Building" and "Browse by How You're Working" sections with a brief description that clearly explains its purpose. Include a link to the server's directory using the pattern `src/your-server-name/`. Ensure your server's description is consistent with the style of existing entries.

GitHub provides additional document on [forking a repository](https://help.github.com/articles/fork-a-repo/) and
[creating a pull request](https://help.github.com/articles/creating-a-pull-request/).

## Finding contributions to work on

Looking at the existing issues is a great way to find something to contribute on. As our projects, by default, use the default GitHub issue labels (enhancement/bug/duplicate/help wanted/invalid/question/wontfix), looking at any 'help wanted' issues is a great place to start.

## Code of Conduct

This project has adopted the [Amazon Open Source Code of Conduct](https://aws.github.io/code-of-conduct).
For more information see the [Code of Conduct FAQ](https://aws.github.io/code-of-conduct-faq) or contact
[opensource-codeofconduct@amazon.com](mailto:opensource-codeofconduct@amazon.com) with any additional questions or comments.

## Security issue notifications

If you discover a potential security issue in this project we ask that you notify AWS/Amazon Security via our [vulnerability reporting page](http://aws.amazon.com/security/vulnerability-reporting/). Please do **not** create a public github issue.

## Licensing

See the [LICENSE](LICENSE) file for our project's licensing. All contributions must be made under the terms of the Apache 2.0 license. You confirm this by including the required contributor statement in your pull request description (see [Contributing via Pull Requests](#contributing-via-pull-requests) section above).
