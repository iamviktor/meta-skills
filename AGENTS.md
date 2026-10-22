# Repository guide

## Purpose

meta-skills is a collection of links to third-party AI agent skills, skill collections, tools, plugins, books, and cookbooks, each with a short description. Keep the collection in resources.md and link to it from README.md.

## Editing the collection

- Use this entry format: `- [Resource name](https://canonical-source-url) by Author — Short description.`
- Link to the original author's repository or official page. Preserve author credit.
- Describe what the resource does in one sentence. Use factual language and avoid unsupported claims.
- Check for an existing entry before adding a resource. Update duplicate or outdated entries instead of adding another copy.
- Use the existing categories: Skills for individual skills and collections; Skills for Deutsches Recht for German-law and related legal workflow resources; Tools for tools and plugins; Books for books, cookbooks, and educational notebook collections.
- Describe each resource's actual scope, including experimental status or coverage beyond German law where relevant. A category does not imply German-law specialization.
- Add category headings only when they help readers browse.
- Keep README.md's category links in sync with resources.md when headings change.
- Keep this repository focused on links and descriptions. Do not copy third-party resource contents or add application code, dependencies, or build tooling unless requested.

## Verification

- Open new or changed URLs and confirm that the destination matches the name, author, and description. If you cannot verify a link, say so in your handoff.
- Review Markdown formatting and the diff for unintended changes.
- Check relative file links and section anchors when editing navigation.
- Documentation edits need no build or test suite.
