---
layout: default
title: Home
---

# System Logs

> Last login: {{ site.time | date: "%a %b %d %H:%M:%S" }} on ttys001

Welcome to the archive. This node stores CTF writeups and research notes.

### Directory Listing: ./posts/

| Permissions | Date | Size | File Name |
| :--- | :--- | :--- | :--- |
| `drwxr-xr-x` | Dec 05 | 4096 | **[../ (Parent Directory)](/)** |
| `-rw-r--r--` | Dec 04 | 12kb | **[Buffer_Overflow_Guide.md](/posts/buffer-overflow)** |
| `-rw-r--r--` | Nov 20 | 8kb  | **[HackTheBox_Machine_Walkthrough.md](/posts/htb-walkthrough)** |
| `-rwx------` | Oct 15 | 2mb  | **[Private_Research_Notes.txt](/posts/private)** |

<br>

### Active Processes

{% highlight bash %}
PID   USER     PR  NI  VIRT  RES   SHR S  %CPU  COMMAND
1337  root     20   0  160m  40m   5m  S   0.0  ./capture_the_flag.sh
1338  root     20   0  110m  20m   4m  S   0.0  python3 visuals.py
{% endhighlight %}
