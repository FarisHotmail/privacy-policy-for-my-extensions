# Privacy Policy for Tab Network Traffic Monitor

**Last Updated:** 24 October 2023

This Privacy Policy describes how the "Tab Network Traffic Monitor" Chrome extension (the "Extension") handles your information. Your privacy is important to us, and we are committed to protecting it.

## 1. Data We Do NOT Collect

The Extension is designed with user privacy as a core principle. We **do not** collect, store, transmit, or sell any of your personal data. This includes:

*   Your browsing history.
*   Your personal identifiable information (name, email, etc.).
*   Data from your web accounts.
*   Your IP address or location data on our servers.

## 2. Data Handled Locally

The Extension operates entirely on your local machine within your Chrome browser. All data processing occurs locally.

*   **Network Request Data:** The Extension uses the `chrome.webRequest` API to analyze network traffic (such as domain names, IP addresses, and data size) for the browser tabs you choose to monitor. This information is **only displayed to you** within the extension's interface and is **never sent to any remote server** controlled by us. This data is discarded when the tab is closed or you close the extension popup.
*   **User Settings:** The Extension uses the `chrome.storage.local` API to save your language preference. This setting is stored only on your local computer and is not transmitted anywhere.

## 3. Data Sent to Third-Party Services

For enhanced functionality, the Extension makes direct, user-initiated requests from your browser to the following third-party services. We do not act as an intermediary for these requests, and we do not see or store the data exchanged.

*   **Google DNS API (`dns.google`):** To resolve a domain name into an IP address, a request is sent to Google's public DNS service.
*   **IP Geolocation API (`ip-api.com`):** To provide WHOIS information (like country and ISP) for an IP address, a request is sent to this public API.

The use of these services is subject to their respective privacy policies. The Extension only sends the necessary domain or IP address for the lookup and does not include any personal information in these requests.

## 4. "Save Data" and "Open Report" Features

The "Save Data" and "Open Report" features are entirely local.
*   When you click "Save Data", the traffic analysis data is saved as a `.json` file **directly to your computer**. This data is never transmitted to us.
*   When you use "Open Report", the selected file is read by your local browser to be displayed within the extension. The file content is not uploaded or sent anywhere.

## 5. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page.

## 6. Contact Us

If you have any questions about this Privacy Policy, please feel free to open an issue on the project's GitHub repository.

---
