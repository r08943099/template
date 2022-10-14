
title: Post-mortem
created at: Fri Oct 14 2022 07:06:03 GMT+0000 (Coordinated Universal Time)
updated at: Fri Oct 14 2022 07:11:07 GMT+0000 (Coordinated Universal Time)
---

# Post-mortem

## Date: type /today

## Author: @mention

# TL;DR;

Explain in a few lines what happened during this event.

# Timeline

Detail the timeline of events that lead to the event

| Time             | Event |
| ---------------- | ----- |
| **13:13 UTC**    |       |
| **13:14 UTC**    |       |
| **13:14:52 UTC** |       |
| **13:15 UTC**    |       |
| **13:17 UTC**    |       |

# Why

This is where technical details could become handy

**Logs generated**

```raw

       host: unknown
      start: 2020 Jan 30 22:58:13.219
        end: 2020 Jan 31 12:14:19.839
date format: iso8601-local
   timezone: UTC
     length: 112701
     binary: unknown
    version: >= 3.0 (iso8601 format, level, component)
    storage: unknown

DISTINCT
       3  Error sending response to client: ... . Ending connection from ... (connection id: ... )
       2  Sessions collection is not set up; ... waiting until next sessions refresh interval:
       2  Test -
       2  Error connecting to ... :
       2  Scheduling catchup takeover at
       2  Canceling catchup takeover callback
       1  dry election run succeeded, running for election
       1  Push: ... ( ... )
       1  Failed to connect to ... -

distinct couldn't match 185 lines
to show non-matched lines, run with --verbose.
```

# 

# Next steps

What are the next steps to implement to avoid having this issue again?

          