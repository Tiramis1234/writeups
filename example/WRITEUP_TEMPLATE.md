# Challenge Name

**Platform:** TryHackMe
**Difficulty:** medium
**Tags:** web, privesc

## Summary

One paragraph overview of the box — what kind of machine it is, its theme, and the main
vulnerability chain you'll exploit. Keep it spoiler-light.

---

## Recon

### Port scan

```bash
nmap -sC -sV -oN nmap.txt <target-ip>
```

```
# paste relevant nmap output here
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8.9 ...
80/tcp open  http    Apache httpd 2.4 ...
```

### Web enumeration

```bash
gobuster dir -u http://<target-ip> -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt
```

---

## Exploitation

Describe the vulnerability and how you identified it.

```bash
# commands used to gain initial foothold
```

Screenshot or paste of proof (e.g. shell prompt, first flag file).

---

## Privilege Escalation

### Enumeration

```bash
# e.g. linpeas, sudo -l, find / -perm -4000, etc.
```

### Exploitation

Step-by-step from low-priv shell to root.

```bash
# commands used
```

---

## Flags

| Flag     | Value               |
|----------|---------------------|
| user.txt | `abc123...`         |
| root.txt | `def456...`         |

---

## Key Takeaways

- What was the core vulnerability or technique?
- Any tools or tricks you want to remember?
- What would you do differently next time?

---

## Tools Used

`Nmap` `Gobuster` `Burp Suite`
<!-- list only what you actually used -->
