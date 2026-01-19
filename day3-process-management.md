# Day 3 – Linux Process Management

## What is a Process
A process is a running instance of a program managed by the Linux kernel.

---

## PID (Process ID)
PID is a unique number assigned to every running process in Linux.  
It is used to identify, monitor, and control processes.

---

## PPID (Parent Process ID)
PPID is the PID of the process that started the current process.  
It helps in tracing the process hierarchy and understanding how a process was created.

---

## TTY (Terminal)
TTY shows the terminal or session from which a process was started.

- pts/*  → Terminal session
- tty7   → Graphical desktop session
- ?      → Background/system process

---

## Important Process Commands

### Check a specific process
```bash
ps -p <PID>
