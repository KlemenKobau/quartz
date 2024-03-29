# Namespaces

- [Separation Anxiety: A Tutorial for Isolating Your System with Linux Namespaces](https://www.toptal.com/linux/separation-anxiety-isolating-your-system-with-linux-namespaces)
- [Man namespaces](https://man7.org/linux/man-pages/man7/namespaces.7.html) - Link or run `man namespaces`.

## Namespace types

- IPC
- Network
- Mount
- PID
- Time
- User
- UTS

## Cgroups
- How is this different?
  - Namespaces set the visibility of resources, cgroups set the quota

Relevant: [[Kubernetes]], [[Containers]]

# Audit

Linux has a built in auditing functionality **The Linux audit framework**.
It runs with *systemd* and is described in more detail in https://wiki.archlinux.org/title/Audit_framework