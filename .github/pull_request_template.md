### Description:

<!--
This should be a brief description of the PR. Details should be contained in commit messages

The PR should be restricted to only two or three changes. For adding new dashboards this should be done over more than one PR due to the size of the JSON files for dashboards.

Examples of summary of changes:
- Which dashboards were updated
- If new dashboards were created, a summary of what the dashboards will show

-->

### Additional Notes

<!-- This section can be removed if not required 

-->

---

### Submitter:

Have you:

* [ ] Checked the latest commit runs on a Grafana instance using the aq personality `openstack-grafana`?
  
* [ ] Dashboards have clearly labelled panels, and are easy to read?


### Reviewer:

As part of reviewing this PR the changes must be tested on a Grafana instance. To do this:

* [ ] Spin up a machine with the aq personality `openstack-grafana`

* [ ] In `/etc/grafana/grafana.ini` under `[server]` comment out: domain, root_url, http_addr. Restart Grafana

* [ ] As Root change the git branch the dashboard folder (`/etc/grafana/provisioning/dashboards`) using: `git switch <branch-name>`
  
Have you:

* [ ] Checked whether the panels are clear and easy to read?

