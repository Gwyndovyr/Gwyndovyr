<div align="center">

# `gwyn`

**Linux · Backend · Security · Robotics**

```text
┌─────────────────────────────────────────────────────┐
│ gwyn@arch ~ $ ./profile                             │
│                                                     │
│ SYSTEM                                              │
│ ├─ OS        Arch Linux                             │
│ ├─ WM        Hyprland                               │
│ └─ Shell     Fish                                   │
│                                                     │
│ DEVELOPMENT                                         │
│ ├─ Java      ████████████████████  loaded           │
│ ├─ Backend   █████████████████░░░  active           │
│ └─ Database  ████████████████░░░░  active           │
│                                                     │
│ OTHER                                               │
│ ├─ Linux                                            │
│ ├─ Robotics                                         │
│ └─ Security                                         │
└─────────────────────────────────────────────────────┘
```

</div>
     
## `$ systemctl status gwyn.service`

## `$ systemctl status gwyn`

```text
● gwyn.service - Personal Development Environment
     Loaded: loaded
     Active: active (running)
   Processes: 5

Sep 25 17:42:01 arch gwyn[1000]:
    Starting backend.service...

Sep 25 17:42:01 arch gwyn[1000]:
    Java runtime initialized

Sep 25 17:42:02 arch gwyn[1000]:
    database.service started

Sep 25 17:42:02 arch gwyn[1000]:
    linux.service started

Sep 25 17:42:03 arch gwyn[1000]:
    robotics.service started

Sep 25 17:42:03 arch gwyn[1000]:
    security.service started

Sep 25 17:42:03 arch gwyn[1000]:
    All systems operational.
```
<details>
<summary>security.service logs</summary>

```text
$ journalctl -u security.service

[ OK ] Linux security
[ OK ] Network fundamentals
[ OK ] Security concepts
[ OK ] Penetration testing
```

</details>

## `$ ls ~/projects`

```text
backend/      databases/      linux/
robotics/     automation/     [REDACTED]/
```

<div align="center">

```text
$ systemctl status gwyn

● gwyn.service - learning
     Active: running
```

`"it works on my machine."`

</div>
