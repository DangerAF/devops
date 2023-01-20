# DevOps Standard

<details>
<summary>Preview</summary>

{% highlight ruby %}
puts 'Expanded message'
{% endhighlight %}

</details>

Mind map

https://mm.tt/1913675247?t=HKWyZ5Fcoa

(todo) remove colors, flags, etc.

### DevOps classic responsibilities

https://aws.amazon.com/devops/what-is-devops/

- infrastructure
- monitoring
- incident management
- CI/CD
- (extra) release process
- (extra) data pipelines

### Devops extra responsibilities

- databases/DBA, data streams, data warehouses, ETL.

### Artifacts / Links

- DevOps spreadsheet, tabs = (???).
- How to: quick help.
- Troubleshooting: most frequent issues.
- performance review reports (weekly).
- system/network diagram.
- clusters/apps list  (name, URL, APM service URL, ?).
- services list.
- devops calendar.
- domains / DNS.
- certificates.
- ops pager (e.g. OpsGenie).
- uptime monitoring service (e.g. StatusCake).
- system status page (e.g. Atlassian StatusPage).
- CI/CD system.
- maintenance window = ?

extra:
- infrastructure envs Slack channels.

### KPIs

Scheduled "preformance review" meetings.

- uptime: by apps.
- performance:
    - number of processed requests (total, by apps), avg. response time by apps.
    - most frequent errors.
    - slowest endpoints.
- errors: timeouts, 500s, crashes by apps.
- capacity: CPU/mem/IOPS/space metrics & trends by apps.
- CI/CD: number of runs, avg exec time by pipelines.

Services: any alerts, issues?

Actions:
- tickets: fix critical apps errors.
- tickets: fix most frequent apps errors.
- tickets: do apps optimization: slow endpoints, etc.
- tickets: infrastructure upgrades.
- tickets: service optimization (create db indexes, etc.).

### New Infrastructure

- setup
- monitoring
- backups (Db, etc.)
- security (enable user accts MFA)
- continuous deployment

### Monitoring

- SLA: uptime (health/ping), availability, latency, correctness.
- Apps
    - uptime -> alert.
    - response time -> alert.
    - CPU/memory/disk-space -> alert.
    - errors: timeouts, 500s, crashes -> daily report.
- Services
    - CPU/memory/disk-space -> alert.
    - Incidents (status pages email subscription) -> alert (Slack, dev-services channel).
- Integrations: ops pager (OpsGenie), Slack.

### Incidents management

https://postmortems.pagerduty.com/resources/post_mortem_template/

### CI/CD

- Jenkins, CircleCI, BitBucket Pipelines, Buddy, CodeShip.
- requirements: automation, Docker and docker-compose support.

### Release process

- trunk-based development or GitFlow?
- https://trunkbaseddevelopment.com/

### Apps orchestration & recovery

- CPU/mem watcher/restarter.
- errors (timeouts, etc.) watcher/restarter.

### Communication

- Slack
    - devops, devops-access, devops-data
    - dev-services
    - env-dev/qa/stage/uat/prod

### Resources

https://aws.amazon.com/devops/what-is-devops/

https://www.reddit.com/r/devops/

