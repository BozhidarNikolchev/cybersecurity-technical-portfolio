---
Author: Bozhidar Nikolchev  
---

# Tor Verification

## Why Verification Matters

- Prevents tampering  
- Ensures authenticity  
- Protects against malicious downloads  

---

## Import Tor Key

gpg --keyserver hkps://keys.openpgp.org --recv-keys 0xEF6E286DDA85EA2A4BA7DE684E2C6E8793298290

---

## Verify Signature

gpg --verify tor-browser-linux-x86_64.tar.xz.asc

---

## Expected Output

Good signature

---

## Key Insight

Trust should always be verified, not assumed.
