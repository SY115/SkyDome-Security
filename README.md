# SkyDome Security | 天穹安全系统

> A self-protecting security shell for Windows. Once running, nothing can kill it.

## What is this?

SkyDome is a Windows security layer with one core principle:
**It protects itself.**

Most security software gets killed first when attacked. SkyDome doesn't.

## Key Features

- **Ring 0 Kernel Driver** — Process unkillable at OS level. Task Manager returns "Access Denied"
- **Dual-Process Guardian** — Two processes watch each other. Kill one, the other revives it
- **Syscall Hook Injection** — Intercepts dangerous commands before execution
- **Immutable Audit Chain** — Every attack attempt is logged, cannot be tampered
- **Network Kill-Switch** — Cuts network access if data exfiltration is detected
- **Anti-Brute-Force** — Wrong password 3 times = permanent lockout
- **Registry Persistence** — Survives reboots

## Why I built this

AI agents like OpenAI Operator can now control computers automatically.
If an AI goes rogue or gets hijacked, you need something it cannot bypass or shut down.
SkyDome is that thing.

## Built by

22-year-old, no coding background, built with AI assistance in 5 days.

## Contact

LinkedIn: linkedin.com/in/jiayi-sun-7240653b9
Google email: beltaneshulenberger@gmail.com
