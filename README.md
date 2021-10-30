# Project Description
This is project is focused on run a spider to download the img

## Technologies we are using
- python

### Guides

#### Start the service locally

Then run the application using command:
```shell
# this command can build up postgres

```
Once the server starts, navigate to `http://localhost:8080/swagger-ui.html` to view API docs for this service

#### Test
The gradle test command will run test individually, using command:
```shell
./gradlew test
```

### Git Commit Message

#### Format
`<type>(<jira_id>): <scope>`
The `type` must be one of the following:
- build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- ci: Changes to our CI configuration files and scripts (example scopes: Circle, BrowserStack, SauceLabs)
- docs: Documentation only changes
- feat: A new feature
- fix: A bug fix
- perf: A code change that improves performance
- refactor: A code change that neither fixes a bug nor adds a feature
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- test: Adding missing tests or correcting existing tests
- release: Changes about release such as bumping the version in package.json
  Note:
  If your card is not related to any JIRA card, just use `N/A` for the `<jira_id>`.

#### Example

```
feat(SP-1): add button component
fix(SP-2): adjust animation effects
fix(N/A): UI enhancement for button
release(N/A): new version 1.0.0
```

