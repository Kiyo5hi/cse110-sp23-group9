# CI/CD Pipeline Phase 1

- [x] linting and code style enforcement (may happen in pipeline and/or in editor)
- [ ] code quality via tool  (ex. Codeclimate, Codacy, etc.)
- [x] code quality via human review (ex. Pull Requests)
- [x] unit tests via automation (ex. Jest, Tape, Ava, Cypress, Mocha/Chai, etc.)*
- [ ] documentation generation via automation (ex. JSDocs)

## Currently Functional 

### - Linting and Code Style Enforcement
`eslint` + `prettier`

### - Code Quality via Human Review (Pull Requests)
For any pull request, at least 1 approving review by other team member is required to merge it to the main branch.

Besides, when creating any pull request, the [pull request template](../../docs/pull_request_template.md) automatically appeared on the pull request description should be appropriately filled in. This includes: 
- the number of which issue it solved
- renaming branch to have name like `<feature/<username>/<3-4 word description separated by dashes>`
- the changes it made
- For dev team, also includes: 
  - testing of the changes
  - screenshot or video of the changes or how to see the changes

### - Unit Tests via Automation
`Jest` is a delightful JavaScript Testing Framework with a focus on simplicity that we used in our CI/CD pipeline. It will scan the entire project, detect all the `**/*.test.js` file, and run all the content to perform unit tests. 

## Planned/In Progress 
TBD

## Diagram of Phase 1 Build Pipeline