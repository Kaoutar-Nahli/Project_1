Provide a short summary in the Title above. Examples of good PR titles:* "Feature: add so-and-so models"
* "Fix: deduplicate such-and-such"
* "Update: dbt version 0.13.0"
## Description & motivation
Describe your changes, and why you're making them. Is this linked to an open issue, a DevOps ticket, or another pull request? Link it here.
## Screenshots:
Include a screenshot of the relevant section of the updated DAG. You can access your version of the DAG by running `dbt docs generate && dbt docs serve`.
## Pull request checklist
- [ ] My pull request represents one logical piece of work.
- [ ] My commits are related to the pull request and look clean.
- [ ] My SQL follows the [style guide](https://github.com/HD-Underwriting/quote-market-data/blob/development/guides/sql_style_guide.md).
-- [ ] I have added appropriate tests and documentation to any new models.
## Table(s) info
| dbt model name  | grain/pk | materialization |
![image](https://user-images.githubusercontent.com/84411806/233396489-19722e80-cb7d-4b8f-b88e-944df2a7c1e5.png)
