# DevOps Playbook

Mind map

https://mm.tt/1913675247?t=HKWyZ5Fcoa

(todo) remove colors, flags, etc.

### DevOps classic responsibilities

- infrastructure
- monitoring
- incident management
- CI/CD

### Artifacts / Links

- DevOps spreadsheet, tabs = (???).
- How to: quick help.
- Troubleshooting: most frequent issues.
- performance review reports (weekly).
- system/network diagram.
- clusters/apps list.
- services list (name, URL, ?)
- devops calendar.
- domains / DNS.
- certificates.

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

### Monitoring

- Apps
    - uptime -> alert.
    - response time -> alert.
    - CPU/memory -> alert.
    - errors: timeouts, 500s, crashes -> daily report.
- Services
    - CPU/memory -> alert.
    - memory 
