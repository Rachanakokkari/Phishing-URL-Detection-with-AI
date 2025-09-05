# Phishing-URL-Detection-with-AI

---

## 🔧 How It Works

1. Enter or paste a URL into the input box.
2. Click the **Check** button.
3. The script runs a series of checks:
   - Detects suspicious keywords
   - Checks for IP-based URLs
   - Counts dots in URL
   - Identifies suspicious TLDs
4. Displays **Safe ✅** or **Phishing ❌** with reasons.
5. Dashboard updates in real-time with stats.

---

## 📊 Sample Checks

| URL Example                                | Expected Result |
|-------------------------------------------|----------------|
| `http://192.168.1.10/login`               | ❌ Phishing    |
| `http://paypal.com.account-update.ru`     | ❌ Phishing    |
| `http://free-gift.top/winner`             | ❌ Phishing    |
| `https://www.google.com`                  | ✅ Safe        |
| `https://github.com/`                     | ✅ Safe        |

---

## 🚀 How to Run

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/yourusername/phishing-url-detector.git
