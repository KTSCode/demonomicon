# Store Technical Proposals in GitHub vs. Notion

## Context and Problem Statement
We want to record technical decisions and proposals made across the entire engineering org, independent of whether decisions concern the architecture, the code, or developer experience.
Should we store technical proposals in GitHub using MADR, or continue using Notion?

## Considered Options
- GitHub (using MADR)
- Notion (current system)

## Pros and Cons of the Options

### GitHub (using MADR)

#### Pros:
- PR Reviews on Technical Proposals
- GitHub is comfortable for engineers to use
- Markdown rocks!
- MADR allows for structured capturing of any decision.
- The MADR format is lean and fits our development style.
- The MADR structure is comprehensible and facilitates usage & maintenance.
- Version control and history tracking.
- We can use the repo to store standardized code like ci-config files

#### Cons:
- Changes things
- Requires some kind of integration with notion to give product access
- Potential overhead of setting up and managing a new repository.
- Limited access/visibility for non-engineers without GitHub accounts.

### Notion

#### Pros
- Requires no change
- Everyone can access it
- Familiar interface and workflow for all employees.

#### Cons
- Makes it hard to track feedback and changes on a technical proposal
- Less structured format compared to MADR.
- Lack of version control and history tracking in the same way as GitHub.

## Decision Outcome
Chosen option: "", because
