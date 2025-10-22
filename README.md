
# 🧠 Phishing Email Analysis

## 📌 Objective
Analyze a suspicious email to detect phishing indicators through header, body, and link inspection.

---

## 🧩 Steps Covered
1. **Header Analysis** – Check sender authenticity and SPF/DKIM.  
2. **Body Analysis** – Spot urgency, fake alerts, or grammar issues.  
3. **Link Inspection** – Verify URLs without clicking.  
4. **Risk Assessment** – Combine all findings for a final verdict.

---

## 📁 Files
| File | Description |
|------|--------------|
| `headers-analysis.md` | Step 3 – Email header breakdown |
| `body-analysis.md` | Step 4 – Body content review |
| `link-analysis.md` | Step 5 – Safe link inspection |
| `risk-assessment.md` | Step 6 – Overall phishing verdict |

---

## ✅ Summary
The email pretended to be from **Microsoft**, but used:
- **Fake domain:** `m1crosoft-security.com`  
- **Failed SPF/DKIM** checks  
- **Urgent tone** and **threat of suspension**  
- **Suspicious link** to a non-Microsoft site  

**Verdict:** 🚨 *Confirmed phishing attempt.*

---

## 🛡️ Recommendation
- Don’t click links or reply.  
- Report and delete the email.  
- Verify senders by checking domain and headers.

---

> Created for cybersecurity training to identify phishing red flags.
