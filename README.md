# ⚡ Shadow Key API

> Automated Windows product key generation via REST API.
> Generate up to 512 keys per request. 

💬 **Contact & Order:** https://t.me/Bin_Yong

---

## Features

- ⚡ Instant generation — results in milliseconds
- 📦 Batch support — up to **512 keys per request**
- 💰 Pay-as-you-go —, no subscription
- 🔐 Bearer token authentication
- 🌍 Works with Python, Node.js, PHP, curl...

---

## Quick Start

```bash
curl -X POST https:/api/generate \
  -H "Authorization: Bearer YOUR_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"keys": ["XXXXX-XXXXX-XXXXX-XXXXX-XXXXX"], "count": 10}'
