# Default Policy Template

The policies.json provided is to be used as an initial baseline to protect enterprise policies that your organization decides to enforce. You can find policy options note from Mozilla [here](https://mozilla.github.io/policy-templates/) to configure.

## Default Settings in policies.json Example

```json
"EnterprisePoliciesEnabled": true
```
   MacOS requirement to use of enterprise policies in Firefox.

```json
"BlockAboutConfig": true
```
   Disables access to about:config page to prevent unauthorized changes. 

```json
"BlockAboutProfiles": true
```
   Disables access to about:profiles page to prevent unauthorized profile management.

## Recommendations from [Policies Template](https://mozilla.github.io/policy-templates) to get started: 

[Homepage](https://mozilla.github.io/policy-templates/#homepage)
    - Set a default homepage and how new Firefox sessions start

[Managed Bookmarks](https://mozilla.github.io/policy-templates/#managedbookmarks)
    - Configure a set of managed bookmarks (Favorites) that users cannot change.

[Extensions Settings](https://mozilla.github.io/policy-templates/#extensionsettings)
    - Force install extensions required for enterpise security and functionality
    - Create a blocklist for extensions that are not allowed or have security risks.

[Enable Tracking Protection](https://mozilla.github.io/policy-templates/#enabletrackingprotection)
    - Enable tracking protection in Firefox for users browsing the webpages

[Disable Usage Reporting to Mozilla](https://mozilla.github.io/policy-templates/#disabletelemetry)
    - Disable upload of usage and crash data (telemetry data) to Mozilla. 
        **Please Note:** Mozilla recommends that you do not disable telemetry data collection. 

[Application Updates](https://mozilla.github.io/policy-templates/#appupdatepin)
    - Prevent automatic updates to beyond a specified version for consistency across the organization and prevent potential vulnerabilities.

[Override Welcome (first-run) Experience](https://mozilla.github.io/policy-templates/#overridefirstrunpage)
    - Disable / Override the first-run experience to streamline the initial setup for users

[Disable Firefox Account Sync](https://mozilla.github.io/policy-templates/#disablefirefoxaccounts)
    - Disable usage of Firefox Account sync for users