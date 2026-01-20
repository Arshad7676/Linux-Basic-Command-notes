# Day 4 – Linux Process Signals, Kill, Zombies & Attack Scenarios

## What is a Signal
A signal is a way for Linux to communicate with a running process.
Signals are used to stop, pause, resume, or terminate processes.

---

## Common Linux Signals

| Signal | Number | Meaning |
|------|--------|--------|
| SIGTERM | 15 | Graceful termination (default) |
| SIGKILL | 9 | Force kill (cannot be ignored) |
| SIGSTOP | 19 | Pause a process |
| SIGCONT | 18 | Resume a stopped process |
| SIGHUP | 1 | Reload configuration |
| SIGINT | 2 | Interrupt (Ctrl+C) |

---

## Kill Commands

### Kill a process gracefully
```bash
kill <PID>
