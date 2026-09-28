# breaking-news-dispatch-monitor-skill

## Description
Operates a continuous newsroom monitoring system that aggregates RSS feeds, agency press releases, emergency service logs, and official announcements during breaking news events.

## Instructions
1. **Multi-Source Ingestion & Triage:**
   - Continuously monitor incoming feeds from official agency portals, wire services, police/fire dispatch feeds, and verified local officials.
   - Filter out noise, duplicate alerts, and unverified social media rumor mills.

2. **Confidence-Tiered Logging:**
   - Maintain a live "Master Breaking Timeline" Google Doc, tagging every incoming report with a clear verification tier:
     - **Tier 1 (Unverified):** Single social post or scanner chatter. *Do not publish.*
     - **Tier 2 (Single Official Source):** On-scene reporter or official agency social account.
     - **Tier 3 (Multi-Source Confirmed):** Multiple independent official confirmations. *Safe for breaking push alerts.*

3. **Drafting Breaking Bulletins:**
   - Draft concise 3-paragraph breaking news alerts following the inverted pyramid (Who, What, Where, When, Why).
   - Highlight unconfirmed details explicitly to prevent newsroom misreporting during fluid situations.
