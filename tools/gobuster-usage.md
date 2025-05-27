
---

### 📁 `tools/gobuster-usage.md`

```markdown
# 🛠️ Gobuster Usage – zerodaywarrior

## Scan Web Directories
```bash
gobuster dir -u http://<IP> -w /usr/share/wordlists/dirb/common.txt
gobuster vhost -u http://<IP> -w hosts.txt
