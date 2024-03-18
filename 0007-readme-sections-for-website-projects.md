# 7. README sections for website projects

Date: 2024-03-18

## Status

Accepted

## Context

Website projects have a common set of details and tasks that all
developers who work on the project need to know about.

## Decision

Website projects must include a README.md in the root directory with
the following information

- URL where the site can be accessed
- CMS flavor (e.g. Drupal & which major version, if Wordpress indicate
  Bedrock/Radicle etc.)
- Hosting platform with dashboard link, or at minimum project name
- CI information with link to dashboard/logs
- Local development instructions
- Description of any other project customizations including custom
  theme/module/plugin locations

## Consequences

Developers will be able to get projects up and running with minimal
assistance. READMEs will need to be maintained.
