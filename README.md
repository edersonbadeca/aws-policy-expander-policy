## Privacy Policy – AWS Policy Expander

**Last updated:** 23 February 2026

### Overview
AWS Policy Expander is a Chrome extension whose only purpose is to help users quickly expand all IAM policy detail rows in AWS Management Console tables with a single click. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Data collection and usage
- This extension does not collect, store, or transmit any personal or sensitive user data.  
- The extension does not log or send any information about the pages you visit, your AWS account, IAM policies, or any other browsing activity to external servers.  
- All logic runs locally in your browser and only interacts with the currently active tab when you explicitly click the extension’s popup button. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### How the extension works
- When you click the extension’s popup button, it injects a small script into the active tab using the Chrome Scripting API.  
- This script searches the current AWS Management Console page for buttons matching `button[data-testid="expand"][aria-expanded="false"]` and programmatically clicks them to expand the corresponding IAM policy details.  
- The extension does not modify any data in your AWS account; it only changes the way information is displayed in the browser UI. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Permissions
The extension requests the following Chrome permissions, strictly to support its single purpose:

- `activeTab`: Allows the extension to run its script only on the tab that you are actively viewing when you click the popup button, so it can interact with the AWS Management Console page you already have open.  
- `scripting`: Allows the extension to inject and execute a static script in the active tab in order to find and click the expand buttons for IAM policies. No remote code is loaded or executed. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Third parties and data sharing
- The extension does not send data to any third-party services.  
- The extension does not sell, rent, or transfer user data to third parties. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Cookies and tracking
- The extension does not set or read any cookies.  
- The extension does not include analytics, tracking scripts, or advertising. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Children’s privacy
This extension is not directed to children and does not knowingly collect information from children. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Changes to this policy
If this privacy policy is updated in the future, changes will be reflected in this document, along with an updated “Last updated” date. [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)

### Contact
If you have any questions about this privacy policy or the extension, you can contact the developer at:  
**Email:** edersonbadeca@gmail.com [chrome.google](https://chrome.google.com/u/1/webstore/devconsole/30c8ff3e-f68b-4f87-a357-e9934d089d2b/cnleocdcbabbjdjemgegpfanchnpacpf/edit/privacy)
