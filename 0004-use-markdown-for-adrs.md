# 4. Use Markdown for ADRs

Date: 2023-04-21

## Status

Proposed

## Context

ADRs should be clear and easy to read. We also want them to be easy to
create. Markdown is version-controllable and readable in raw or rendered
form.

## Decision

We will compose ADRs in Markdown.

## Consequences

- ADRs will be easy to create in familiar code editors, and will appear
  with rich formatting on Github.
- It is not guaranteed that Markdown will capture the structure of ADRs
  in a way that is machine-parseable; this could present challenges if
  we decide to migrate to some other way of managing this content.
