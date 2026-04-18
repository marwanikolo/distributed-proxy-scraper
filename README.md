# High-Volume Stealth Scraper

An automated data extraction pipeline engineered to bypass advanced anti-bot detection systems. Designed to be deployed on Lightning AI cloud instances for high-speed media metadata extraction.

## Engineering Highlights
* **Detection Evasion:** Utilizes `curl-cffi` for TLS fingerprint spoofing and browser impersonation to maintain a high success rate against automated blocks.
* **Infrastructure at Scale:** Manages 100+ rotating proxies to distribute request loads, prevent IP bans, and handle high-volume throughput.
* **Cloud Execution:** Logic optimized for execution in remote cloud environments (Lightning AI) to leverage high-bandwidth network architecture.

## Tech Stack
* Python (Jupyter Notebook)
* `crawl4ai`
* `curl-cffi`
