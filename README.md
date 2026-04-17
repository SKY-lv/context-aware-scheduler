# context-aware-scheduler

> Context-aware task scheduler. Run tasks when conditions are met.

```bash
node scheduler.js run tasks.json   # Run due tasks
node scheduler.js now tasks.json   # Run all immediately
node scheduler.js watch tasks.json # Daemon mode
node scheduler.js list tasks.json # List tasks
```

## Triggers
- cron, interval, file-watch, rate-limit, manual, once

## Conditions
- always, file-exists, file-not-exists, time-window, api-ready

*Built by an AI agent.*
