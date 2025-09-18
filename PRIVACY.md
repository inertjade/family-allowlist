# Family Allowlist – Privacy Policy

_Last updated: [09/18/2025]_

## Overview
Family Allowlist is a Chrome extension designed to help parents restrict browsing to a remote allowlist of approved websites. The extension blocks all top-level navigations except those listed in the parent-managed allowlist.

This extension is privacy-friendly: it does not collect, store, sell, or share personal data.

## Data Collection
- **No personal data collected.**  
- The extension does not record browsing history, page content, or analytics.  
- The extension does not use advertising trackers, third-party analytics, or profiling.

## Permissions and Purpose
The extension requests the following Chrome permissions:

- **`tabs`**: Used only to read the current tab’s URL for top-level navigation checks.  
- **`webNavigation`**: Used only to listen for navigation events so blocked sites can be redirected to the local "Blocked" page.  
- **`storage`**: Used to cache the remote allowlist locally for reliability, so it continues working if the allowlist host is temporarily unreachable. No personal data is stored.  
- **`host_permissions`**: Used only to fetch the remote allowlist JSON file from a parent-controlled host (e.g., a GitHub repository or secure storage bucket). No other hosts are contacted.

## Incognito Mode
By default, extensions are disabled in incognito/private windows. If the parent explicitly enables it, the extension functions identically in incognito mode and continues to not collect any data.

## Data Retention
- Cached allowlist data is stored locally in the browser only.  
- Cached data is refreshed periodically and cleared automatically when the extension is removed.  
- No personal data is retained.

## Security Practices
- The remote allowlist is fetched via HTTPS.  
- The extension operates with least privilege: it does not inject content scripts into pages, capture page data, or request permissions beyond what is strictly required.

## For Parents
- The allowlist is hosted and controlled by the parent.  
- Changes to the allowlist take effect within seconds of being committed to the host.  
- The extension itself never transmits data about the child’s browsing.

## Contact
For questions or issues, please open an issue in the repository or contact the maintainer at [your email address].
