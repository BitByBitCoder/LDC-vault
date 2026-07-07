# 07 — Email
[[💻 Computer Knowledge — INDEX|← Back to Index]]

---

## Questions From Your Papers

| Question | Answer |
|----------|--------|
| Email body contains | **Main message content** |
| Email encryption ensures | **Protection of message confidentiality** |
| During email routing messages | **Transferred through series of mail servers** |
| Signature file in email | **Automatically adds contact details to every email** |
| Unwelcome email called | **Spam** |
| Spam is also called | **Junk mail** |

---

## Email Structure

| Part | Contains |
|------|---------|
| **From** | Sender's email address |
| **To** | Recipient's email address |
| **CC** (Carbon Copy) | Secondary recipients — all can see |
| **BCC** (Blind Carbon Copy) | Hidden recipients — others cannot see |
| **Subject** | Brief description of email |
| **Body** | **Main message content** |
| **Attachment** | File sent with email |
| **Signature** | **Auto-added contact info at bottom** |

---

## Email Protocols

| Protocol | Full Form | Purpose |
|---------|-----------|---------|
| **SMTP** | Simple Mail Transfer Protocol | **Sending** email |
| **POP3** | Post Office Protocol v3 | **Receiving** — downloads to device |
| **IMAP** | Internet Message Access Protocol | **Receiving** — stays on server |

### SMTP vs POP3 vs IMAP
| SMTP | POP3 | IMAP |
|------|------|------|
| Sending | Receiving | Receiving |
| Server to server | Downloads email | Email stays on server |
| Port 25/587 | Port 110 | Port 143 |

---

## Email Security

| Feature | Purpose |
|---------|---------|
| **Encryption** | **Protects message confidentiality** |
| **Digital Signature** | Verifies sender's identity |
| **Spam Filter** | Blocks unwanted emails |
| **Antivirus** | Scans attachments for malware |

---

## Email Problems

| Problem | Description |
|---------|-------------|
| **Spam** | Unsolicited bulk email / junk mail |
| **Phishing** | Fake email pretending to be legitimate |
| **Email Bombing** | Sending massive emails to crash inbox |
| **Spoofing** | Fake sender address |

---

## Email Routing

```
Sender → SMTP Server → Internet → Recipient's Mail Server → Recipient
```
> "Transferred through a series of mail servers" — appeared directly in your papers

---

## Exam Traps ⚠️
> Email body = **main message** — NOT routing path or sender address
> Encryption = **confidentiality** — NOT faster delivery or spam filtering
> Email routing = **through mail servers** — NOT directly sender to receiver
> Spam = **unwanted/junk email** — TRUE (appeared as True/False in papers)
> SMTP = **sending** — POP3/IMAP = **receiving**
> CC = all can see recipients; BCC = **hidden** recipients
> Signature file = **automatically adds contact info** — NOT handwritten signature
