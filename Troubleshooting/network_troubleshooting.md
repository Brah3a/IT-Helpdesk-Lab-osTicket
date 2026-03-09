Network Troubleshooting Guide

Problem
User cannot access internet.

**Step 1**
Check network cable or WiFi connection.

**Step 2**
Verify IP configuration.

Command

```bash
    ipconfig
```


**Step 3**
Renew IP address.

Commands

```bash
    ipconfig /release
    ipconfig /renew 
```

**Step 4**
Test connectivity.

Command

```bash
    ping google.com
```

**Step 5**
Check DNS resolution.

Command

```bash
    nslookup google.com
```

**Resolution**
Network restored after renewing IP address.