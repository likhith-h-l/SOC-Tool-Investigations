# VirusTotal Investigation #1. 8.8.8.8 IP Analysis

## 1. IP Address Investigated

**IP Address:** `8.8.8.8`

I looked into the IP address `8.8.8.8` using VirusTotal to find out who owns it what its reputation is and other important information about `8.8.8.8`.

## 2. Basic Information

* **Country:** United States (US)

* **ASN:** AS15169

* **AS Organization:** Google LLC

* **Network:** `8.8.8.0/24`

* **Regional Internet Registry:** ARIN

* **Continent:** North America (NA)

The IP address `8.8.8.8` is located in the United States. Belongs to Google LLC.

## 3. Security Detection

* **Detection Ratio:** `0/91`

* **Malicious Detections:** `0`

* **Suspicious Detections:** `0`

None of the 91 security vendors think `8.8.8.8` is malicious. This is a sign for the IP address `8.8.8.8`.

## 4. Community Reputation

* **Community Score:** `557`

* **Community Activity:** `41.4K`

The community score for `8.8.8.8` is separate from what the security vendors think. So the community score does not mean how antivirus detections there are.

## 5. RDAP / WHOIS Investigation

The RDAP information showed:

* **IP Range:** `8.8.8.0 – 8.8.8.255`

* **CIDR:** `8.8.8.0/24`

* **Network Name:** `GOGL`

* **Organization:** Google LLC

* **RIR:** ARIN

* **Allocation Type:** Direct Allocation

* **Status:** Active

* **WHOIS Server:** `whois.arin.net`

The RDAP and WHOIS information says that the IP range is registered to Google LLC through ARIN. This confirms that `8.8.8.8` belongs to Google LLC.

## 6. Certificate Information

VirusTotal also found a TLS certificate associated with `8.8.8.8`.

Important information included:

* **Certificate Subject:** `dns.google`

* **Certificate Issuer:** Google Trust Services

* **Public Key:** RSA 2048-bit

* **IP Address in Certificate:** `8.8.8.8`

* **Other DNS names:** `dns.google` `dns.google.com` `8888.google`

This provides evidence that `8.8.8.8` is associated with Googles DNS infrastructure.

## 7. My Analysis

Based on my investigation I think `8.8.8.8` is **legitimate**.

I came to this conclusion because of reasons:

1. The IP address `8.8.8.8` belongs to **Google LLC (AS15169)**.

2. VirusTotal shows **0/91 security vendors detecting it as malicious**.

3. RDAP/WHOIS information shows that the IP range is actively allocated to Google through **ARIN**.

4. The TLS certificate is associated with **dns.google**.

5. The IP address `8.8.8.8` is widely known as Googles DNS server.

## 8. SOC Analyst Perspective

If `8.8.8.8` appeared in a security alert I would not close the alert just because it has a `0/91` detection score.

I would also investigate:

* What internal host communicated with the IP address `8.8.8.8`?

* Which process generated the connection?

* What protocol and port were used?

* What DNS queries were made?

* Was the connection expected?

* What was the time and frequency of the communication?

* Are there any domains or files associated with the activity?

## 9. Final

**Classification:** Legitimate

The available VirusTotal intelligence strongly indicates that `8.8.8.8` is a Google-owned IP address associated with Googles DNS infrastructure.

### Key Learning

This investigation taught me that a SOC analyst should not rely on an indicator such as the detection ratio. Instead I should correlate:

**Detection + Reputation + ASN + Ownership + RDAP/WHOIS + Certificate + Network Activity**

to make a reliable security decision, about the IP address `8.8.8.8`.
