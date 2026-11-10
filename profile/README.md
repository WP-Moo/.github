<p align="center">
  <a href="https://wp-moo.com">
    <img src="https://raw.githubusercontent.com/WP-Moo/.github/main/profile/banner.png" alt="Know your WordPress sites are up. Before your client calls." width="100%">
  </a>
</p>

<p align="center">
  <a href="https://wp-moo.com">
    <img src="https://raw.githubusercontent.com/WP-Moo/.github/main/profile/logo.png" alt="WP Moo logo" width="96">
  </a>
</p>

<h1 align="center">WP Moo</h1>

<p align="center">
  <strong>The WordPress monitor that moos when something breaks.</strong><br>
  Uptime and health checks for WordPress and WooCommerce, without a plugin.
</p>

<p align="center">
  <a href="https://wp-moo.com">Website</a> ·
  <a href="https://wp-moo.com/docs">Docs</a> ·
  <a href="https://wp-moo.com/pricing">Pricing</a> ·
  <a href="https://wp-moo.com/roadmap">Roadmap</a> ·
  <a href="https://wp-moo.com/changelog">Changelog</a> ·
  <a href="https://wp-moo.com/waitlist">Join the waitlist</a>
</p>

WP Moo checks your WordPress and WooCommerce sites from the outside, the way a visitor would. There's nothing to install, update or keep compatible. When something breaks, you see it in one clear place, in plain words.

> [!NOTE]
> WP Moo is in an invite-only beta. The beta is free and needs no payment details, and organisations that join during the beta keep [Pro free for life](https://wp-moo.com/pricing). [Join the waitlist](https://wp-moo.com/waitlist) and we'll email you when your invite is ready.

## What it checks

Only what your site and its DNS show the world. Each check can be switched off per site.

| Check | What it watches |
| --- | --- |
| [Pages](https://wp-moo.com/docs/pages) | Your important pages: online, speed, size and content, as often as every minute |
| [SSL & certificate](https://wp-moo.com/docs/checks/ssl) | Expiry, chain and hostname, so you hear well before the padlock stops working |
| [Redirects](https://wp-moo.com/docs/checks/redirects) | http, www and old domains all end up where they should |
| [DNS & mail](https://wp-moo.com/docs/checks/dns) | MX, SPF and DMARC, so mail still reaches you and nobody can easily send as you |
| [Domain](https://wp-moo.com/docs/checks/domain) | Registration and expiry, so the domain doesn't quietly run out |
| [WordPress](https://wp-moo.com/docs/checks/wordpress) | You can still log in, and the REST API that WooCommerce and the editor need still answers |
| [Exposure](https://wp-moo.com/docs/checks/exposure) | Visible PHP, Plesk and WordPress versions that attackers look for |
| [Private files](https://wp-moo.com/docs/checks/files) | Config copies, `.env`, `.git` and error logs that anyone could download |
| [Search engines](https://wp-moo.com/docs/search-engines) | Index, noindex and nofollow per page, the way you want them |

## How it works

- **No plugin.** Nothing runs on your site, so there's nothing to break on the next update.
- **Confirmed before it counts.** A page that looks down is checked again from a second location, so one hiccup isn't a false alarm.
- **One email when it breaks, one when it's over.** Urgent problems reach you right away; smaller ones go in an hourly, daily or weekly digest. Every alert waits 90 seconds, so a short blip sends nothing. [Alerts](https://wp-moo.com/docs/alerts) explains who gets what, and when.
- **Incidents, not noise.** Everything that goes wrong on a site becomes an [incident](https://wp-moo.com/docs/incidents) with its whole story in one place: what it means, what to do, what happened and who was told.
- **Grouped by hosting server.** When a server goes down you see one outage and get one email for all its sites, not a list of offline ones.
- **A priority per site.** A busy webshop is checked every minute, a small brochure site less often.
- **Maintenance mode.** Tell WP Moo you're working on a site, so an update doesn't send alerts or lower its uptime. See [Maintenance](https://wp-moo.com/docs/maintenance).
- **Honest about firewalls.** If a firewall blocks the check, WP Moo shows "Checker blocked" instead of a false alarm.

## Who it's for

- **Site owners** who don't want to learn what an MX record is. WP Moo tells you what broke, how bad it is and what to send your developer.
- **Agencies** who want every client site in one list.
- **SEO agencies** who want to catch a page that turned noindex, a broken redirect or an expiring certificate before the traffic drops.

## What's next

Next up are Slack and Microsoft Teams alerts, a page to share with your developer and alerts in plain words for clients, bulk actions and planned maintenance for large fleets, and IPv6 and Broken links checks. The [roadmap](https://wp-moo.com/roadmap) has the full picture.

## Seeing WPMooBot in your logs?

```text
WPMooBot/1.0 (+https://wp-moo.com/bot)
```

That's our checker. It only visits sites whose owners added them, sends plain GET requests, and never logs in or fills in forms. [Our checker page](https://wp-moo.com/bot) lists exactly what it requests, where it comes from and how to let it in.

## Get in touch

WP Moo is a hosted service, so there's no code to download here. For questions, use the [contact page](https://wp-moo.com/contact).
