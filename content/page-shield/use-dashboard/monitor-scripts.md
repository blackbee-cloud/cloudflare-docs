---
title: Monitor scripts
pcx-content-type: how-to
weight: 2
meta:
  title: Monitor scripts on your site
---

# Monitor scripts on your site

Once you have [activated Page Shield](/page-shield/get-started/), review the **Script Monitor dashboard** to see which scripts are running on your domain. Scripts on the dashboard appear in close to real time, so use the dashboard when proactively looking for scripts. The dashboard only displays scripts last seen within past 30 days.

If you see unexpected scripts on the dashboard, check them for signs of malicious activity.

Depending on your Cloudflare plan, you may also be able to:

- [View the details of each script](#view-script-details)
- [Review scripts marked as malicious](/page-shield/use-dashboard/review-malicious-scripts/)
- [Review changed scripts](/page-shield/use-dashboard/review-changed-scripts/)

## Use the Script Monitor dashboard

To review the scripts tracked by Page Shield:

1.  Log in to the [Cloudflare dashboard](https://dash.cloudflare.com/), and select your account and domain.
2.  Go to **Security** > **Page Shield**.
3.  Under **Script Monitor**, review your scripts.
4.  To filter scripts, use the following options:

    - **Search**: Search for a specific URL.
    - **Host**: Look for scripts appearing on specific hostnames.
    - **Page** (requires a Business or Enterprise plan): Look for scripts appearing in a specific page. Searches the page where the first script occurred and the latest occurrences list.

If you recently activated Page Shield, you may see a delay in reporting.

## View script details

{{<Aside type="note">}}

Only available to customers on Business and Enterprise plans.

{{</Aside>}}

You can check the details of each script displayed in the Script Monitor dashboard, including the following fields:

- **First seen at**: The date and time when the script was first detected.
- **First seen on page**: The page where the script was first detected.
- **Last seen**: How long ago the script was last detected (in the last 30 days).
- **Last seen on pages**: The most recent pages where the script was detected (up to ten pages).

This information helps you track how a script appeared in your domain, and which pages have recently loaded the script.
