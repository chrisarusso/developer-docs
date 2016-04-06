# Redmine

Redmine is our project management tool at [pm.savalabs.com](https://pm.savaslabs.com).
It is **the** authoritative location for project information. It is
ideal to flow as much client communication through the tool as possible for the
purposes of universally-shared documentation outside of personal mailboxes.

To start a project...

## Project settings

- Link Slack channel for updates to post to. If there is a lot of activity on the project, it's customary to create a `[project]-noise` channel to push to.
- Link the repository - have @kostajh fill this out, I think Omega is the only one we have done this for so far.
- Fill out a good description that describes where important assets are like important git branches, dev/staging environments as examples.

### The makings of the _perfect_ task

Writing a task well may be mundane, but is quite important. A few bullet points
 to guide the process are:

- Be specific and detailed
- Assign an estimate - Even if it's, well, an estimate, it provides context
- Assign a person
- Assign a due date
- If applicable, include screenshots
- If applicable, add a parent, sub, or related task (see [Linking issues](#linking-issues))
- If applicable, set target version (see [Sprints](#sprints))

#### Linking issues

It is very helpful to take advantage of the `Related issues` tab on a task.
Here you can specify helpful markers like `related to, blocks, blocked by,
duplicates, duplicated by`

### Sprints

The `Roadmap` tab on the project page provides an interface to assign issues to
a given sprint.

### Project documentation

Add things like RFPs, proposals, mockups, and any other files to the `Files` tab.
@team, can we standardize on
[`Files`](https://pm.savaslabs.com/projects/omega-institute/files) over
[`Documents`](https://pm.savaslabs.com/projects/hptn/documents) and have that as a default
setting on projects? The Documents interface is terrible IMCO (c = correct).

### How to use the wiki

TBD

### Keeping Redmine issues up to date with PRs

TBD

Not sure on this one @kostajh

### Incorporating clients

Perhaps some discussion about adding clients to