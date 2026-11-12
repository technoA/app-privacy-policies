# Mobile Applications Privacy Policies Directory

Central, reusable repository for hosting public, Google Play-compliant and App Store-compliant Privacy Policies across all applications developed by **TAG Systems**.

Hosted live via **GitHub Pages**:
`https://<username>.github.io/app-privacy-policies/<app-folder>/`

---

## Active Applications

| Application Name | Package ID | Privacy Policy Path | Live URL |
| :--- | :--- | :--- | :--- |
| **NexusVPN — Fast Secure Proxy** | `com.tagsys.nexusvpn` | `/nexusvpn/index.html` | `https://<username>.github.io/app-privacy-policies/nexusvpn/` |

---

## How to Add a Privacy Policy for a New App (1 Step)

Adding a privacy policy for any new or upcoming application takes less than 60 seconds:

1. **Create a new subfolder** matching your app's short slug:
   ```bash
   mkdir my-new-app
   ```
2. **Copy the template**:
   ```bash
   cp TEMPLATE/privacy-policy-template.html my-new-app/index.html
   ```
3. **Fill in the brackets**:
   - Replace `[APP_NAME]`, `[PACKAGE_ID]`, `[EFFECTIVE_DATE]`, `[PUBLISHER_NAME]`, and `[CONTACT_EMAIL]`.
4. **Commit and push**:
   ```bash
   git add my-new-app/index.html
   git commit -m "Add privacy policy for My New App"
   git push origin main
   ```
5. **Instant Live URL**:
   Your new privacy policy is immediately reachable at:
   `https://<username>.github.io/app-privacy-policies/my-new-app/`
   Paste this URL directly into the Google Play Console **App Content > Privacy Policy** field!

---

## Compliance Standards

All policies in this repository adhere to:
- Google Play Developer Distribution Agreement & Developer Program Policies
- Mandatory Account & Data Deletion Disclosure (including in-app and web deletion paths)
- Strict Zero-Logs / Permission Disclosures
- TLS / HTTPS encryption requirements for external links

Published by **TAG Systems (Qatar)** | Contact: `2agsystems@gmail.com`
