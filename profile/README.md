# CST 338 Software Design, Online

CSU Monterey Bay, Section 40, Fall 2026 second session. Eight weeks, October 26 to December 21.

Every assignment repository for this course lives in this organization. Your own repositories
appear here once you have joined, and they are private to you and the teaching staff.

## Start here

1. **Join this organization.** You will get one invitation, sent to your `@csumb.edu`
   address. Accept it once and every repository for the rest of the term appears
   automatically, with nothing further to accept.
2. If GitHub does not connect that invitation to your account, your school email is probably
   not on it yet. [Adding your @csumb.edu email to an existing GitHub
   account](https://github.com/cst338-fa26ol/.github/blob/main/docs/add-csumb-email-to-github.md) fixes that, and you do not need a second
   GitHub account.
3. Canvas is where the work is assigned and graded. This organization only holds the code.

## How the week runs

Assignments open and close on **Tuesdays**, and due times are 11:59 PM Pacific.

## Working in your repositories

Commit as you go rather than once at the end, and do your work on a branch:

```bash
git switch -c feature/short-description
# work, commit as you go
git push -u origin feature/short-description
```

Then open a Pull Request on GitHub and merge it there. Do not merge from your machine, and do
not commit straight to `main`.

Use `git switch` to move between branches and `git restore` to throw away a change you do not
want. The older `git checkout` does both of those jobs plus several more, which is how people
delete work they meant to keep.

## Reference

- [Adding your @csumb.edu email to an existing GitHub account](https://github.com/cst338-fa26ol/.github/blob/main/docs/add-csumb-email-to-github.md)
- [Lab: IntelliJ, Rectangle and your first unit test](https://github.com/cst338-fa26ol/.github/blob/main/docs/lab00-readme.md)

## Academic honesty and AI

You are not graded on whether you used an AI tool. You are graded on the work, and on
describing honestly what you did. Where an assignment asks for an AI log, "No AI used" is a
complete answer when it is true.

## Getting help

Office hours and contact details are in Canvas. If a repository is missing or you cannot push
to one, say so early rather than the night something is due.
