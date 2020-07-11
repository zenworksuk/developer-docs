---
name: Writing READMEs
---

There should be a README for every Zenworks GitHub repository. A user expects a README to help them:

- understand what the project is
- evaluate whether the project is useful for them
- learn how to use the project
- understand how to contribute to the project

You should write READMEs in Plain English and define any technical terms that may be unfamiliar to
someone new to the project.

Avoid using terms like 'just' or 'simply' when writing your README. You should not assume your
user has any prior knowledge of your project.

## Length of your README

A README should be an overview and list of instructions to help someone get started with your
project.

If you find yourself writing a lot of content for your README, consider moving some of the more
detailed documentation, such as API reference information or configuration advice, into a separate
document.

We like to include these in a `doc` folder within the same repository and link to them from the
README.

## Structuring your README

Use the following structure for your READMEs:

```md
# README template

This is a template to follow when you write a README for your GitHub repository. Refer to the
[guidance on writing READMEs](https://docs.hq.zenworks.uk/manuals/readme-guidance) for more
information.

## Title your README clearly

Give the user a clear sign they’re looking at the right thing. For example,
`Helpdesk webchat prototype` not `chatbot-v1`.

## Introduce the project

Use the start of your README to describe your project and what it does. Focus on what your project
provides to users or other developers. You can also explain how your project links to other things.

For example:

\`\`\`
help-center is a Node.JS app built on a MySQL database. It’s deployed in 2 modes:
'admin' for publishers to create and manage content
'frontend' for rendering some content under https://help-center.zenworks.uk
\`\`\`

Include any limitations up front so the user can evaluate whether the project meets all their
needs. This includes any version information.

You can also add a table of contents to the start of your README to help users jump to the
information they need.

## Share examples

If applicable, consider adding screenshots or links to live examples of your project so users can
see how other people use your project. You should provided a screenshot of the user-end project.

## Explain any prerequisites

If applicable, list the items a user needs to be able to use your project, such as a certain
version of a programming language. It can be useful to link to documentation on how to install
these items. This could be under a heading such as `Before you start`.

If your project depends on other systems or projects, you should list these technical dependencies.
For example:

\`\`\`
- [zenworksuk/other-repo]() - provides some downstream service
- [redis]() - provides a backing service for work queues
\`\`\`

## Explain how to get started

Next tell the user how to get started with your project. This is often a numbered list on how to
install the project and run it locally. List one action per step.

Follow each step with example code if possible as some users will want to copy and paste directly
from your README.

For example:

\`\`\`
1. Install express.

`npm i express`
\`\`\`

These instructions should help your users get to “hello world” or be able to run the project
locally. If you want to provide more advanced documentation, you could:

- add a configuration section to help the user amend the project for their own use
- speak to a technical writer about publishing separate documentation

## Help users configure and deploy the project for their needs

If applicable, include a link to any editable project configuration files. You should do this
shortly after the ‘getting started’ guidance. You could also:

- list any environment variables available in a table
- link to more detailed configuration documentation in a different file

Describe how to deploy the project if applicable.

## Explain how to test the project

Add information on how users can check they can run the project successfully. For example,
instructions for how to run a test suite.

This can be a useful place to list error messages and suggested fixes.

## Share additional information

This is a good place to link to additional or related information if it’s available such as API
documentation or a separate documentation website.

## Show users where to get support

Let the user know where they can go for help using the project. This could be a support email
address, community forum, or issue tracker attached to the repository.

## Explain how users can contribute

Let users know they can contribute. Consider adding a contribution file (often named
`CONTRIBUTING.md`) with more detail, or state how to contribute in the README.

You can also have a `CODE_OF_CONDUCT.md` file linking to expected communication and behaviour
standards expected of contributors. All open repositories should have a code of conduct.

!!! tip ""
		A standard code of conduct is to come. In the mean time, we suggest using the Contributor
		Covenant

You can also credit individual contributors or link to other repositories that inspired your
project.

## Link to the licence file(s)

All open repositories [must have a copyright licence](https://docs.hq.zenworks.uk/manuals/licensing).
Under a `licence` heading specify the license you’re using and link to the licence file.

Use the [MIT License](https://opensource.org/licenses/MIT) if your repository contains software
code. This license also covers documentation in the repository about that code.
```

## Test your documentation

Test your README instructions before you publish to make sure users can follow your documentation.
You can also ask a:

- member of your team to try the instructions and make sure they work
- technical writer to review the content