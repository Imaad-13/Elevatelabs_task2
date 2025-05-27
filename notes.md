# Phishing Email Analysis Notes

## Sample Email Details
- **Sender Address:** service@intl.paypal.com <service.epayipal@outlook.com>
- **Subject Line:** Response required
- **Date:** 1/29/2016

## Step-by-Step Analysis

1. **Sender Address Analysis:**
   - Displayed address is `service@intl.paypal.com` but actual email is `service.epayipal@outlook.com`
   - Contains a misspelling of "paypal" as "epayipal" — clear spoofing attempt.

2. **Header Check (if available):**
   - Unable to verify here, but typically would check SPF/DKIM/DMARC alignment.

3. **Links Inspection:**
   - "Log in" and "Resolution Center" links not visible directly.
   - Likely lead to phishing pages – would hover over them to see mismatched or suspicious domains.

4. **Language Used:**
   - Urgent and alarming tone: “Response required”, “unusual log in activity”, “temporarily limited”.
   - This is a typical social engineering tactic.

5. **Grammar/Spelling Errors:**
   - No obvious errors in this sample, but structure is robotic.

6. **Visual Inspection:**
   - Brand logo and formatting mimic PayPal’s design, which can trick users.
   - Signature lacks full company info or disclaimers seen in real PayPal messages.

7. **Other Indicators:**
   - No personalized greeting (e.g., "Dear Customer" instead of name).
   - The bottom note says "do not respond to this email", common in fake emails to avoid replies.

---

## Final Notes
Always verify the sender domain, check hyperlinks before clicking, and contact companies directly via official websites. Never trust links in unsolicited emails that create urgency.
