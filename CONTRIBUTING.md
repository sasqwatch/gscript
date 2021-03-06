
# Contributing

## Contributing To Genesis Engine or Compiler
- Must have an associated issue
- Must have an associated PR against the LATEST version of the dev branch
- Must compile without errors for all supported target architectures
- Must pass all linter checks
- Must have an associated unit test(s) written in Golang
- Must include a commit updating any relevant documentation

## Contributing To The Standard Library

- Must have cause to implement the function in Golang (see GOLANG.md)
- Must have an associated issue
- Must have an associated PR against the LATEST version of the dev branch
- Must compile without errors for all supported target architectures
  - If package is OS specific, must be implemented in OS package
- Must pass all linter checks
- Must have an associated unit test(s) written in Golang
- Must have an associated genesis script that implements the function standalone in a gscript for in VM testing
- Must include a commit updating the standard library documentation (using the function template) and include:
  - Name
  - Description
  - Author
  - Method Signature
  - Arguments and their types
  - Returns and their types
  - Example usage
  - How to handle failure
- Must have a revision to the CHANGELOG.md

## Contributing Example Scripts
- PRs must be made against the LATEST version of the dev branch
- Must include typical gscript meta information, including:
  - Title
  - Purpose
  - Author
  - ATT&CK link
  - Note usage
  - Uses link for an bundled assets
- If it compiles to a larger subset of architectures please note that
- Please start an issue on the project if you would like to discuss reorganizing directory structures

## Contributing To Documentation
- PRs must be made against the LATEST version of the dev branch
- Documentation should be done in Markdown unless otherwise specified
- We accept documentation updates with associated issues or code commits
- Updating docs is the recommended way to get familiar with adding to the project
