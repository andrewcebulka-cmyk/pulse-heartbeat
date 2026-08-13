# pulse-heartbeat

A two-field liveness signal written by a local scheduled job as its last step. Deliberately public, deliberately empty of everything else: one JSON file, a date and an ok flag. A cloud watcher reads heartbeat.json raw; a stale date or ok:false is its alarm.
