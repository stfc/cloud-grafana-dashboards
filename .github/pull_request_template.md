### Description:

<!--
This should be a brief description of the PR. Details should be contained in commit messages

The PR should be restricted to only two or three changes. For adding new dashboards this should be done over more than one PR due to the size of the JSON files for dashboards.

Examples of summary of changes:
- Which dashboards were updated
- If new dashboards were created, a summary of what the dashboards will show

-->
---

### Reviewer:

As part of reviewing this PR the changes must be tested on a Grafana instance. To do this:

* [ ] SSH into the dev-grafana instance. `ssh ubuntu@dev-grafana.nubes.rl.ac.uk`
      
* [ ] As Root change the git branch the dashboard folder (`/etc/grafana/provisioning/dashboards`) using: `git switch <branch-name>`
  
* [ ] Restart the Grafana service: `systemctl restart grafana-server`

Have you:

* [ ] Checked whether the panels are clear and easy to read?

* [ ] Changed the branch back to main once the branch is merged
