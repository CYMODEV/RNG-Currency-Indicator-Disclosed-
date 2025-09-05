# RNG-Currency-Indicator-Disclosed-
“rng” and “rung” are proprietary identifiers of Cymos’ native currency and may not be used without express written consent from Cymos Planet governance.
# Cymos Native Currency Disclosure and Ticker Protection

**Currency Name:** rng (pronounced “rung”)  
**Ticker Indicator:** RNG  
**Type:** Fungible digital asset native to the Cymos ecosystem  
**Ledger of Record:** Cymos Ring Ledger (distributed, modular, multi‑ring topology)

---

## 1) Currency identity and purpose
The `rng` token is the native currency of the Cymos platform.

- **Unit of account:** Used for pricing, accounting, and settlement across Cymos rings.
- **Medium of exchange:** Facilitates payments among Applications, Creators, Validators, and Governance.
- **Staking collateral:** Secures Scalar Magnitude validations, creator patronage, and governance proposals.
- **Governance weight:** Confers voting power on protocol parameters and upgrades.

---

## 2) Ticker protection and use policy
Cymos asserts and defends exclusive rights to the **RNG** indicator for identifying the `rng` currency in connection with the Cymos ecosystem and authorized listings.

- **Protected indicator:** RNG (and variants including $RNG, RNG.CYM, RNG‑C, CYM:RNG) are reserved for Cymos’ native currency.
- **Authorized use:** Exchanges, wallets, indexers, and data providers may display “RNG” solely to denote Cymos’ `rng` under a no‑fee, non‑exclusive, revocable license from Cymos Planet governance.
- **Collision protocol:** If an exchange already uses “RNG” for another asset, Cymos authorizes the fallback indicators: “RNG.CYM” or “CYM:RNG”. Do not alias unrelated assets as “RNG” without clear namespace (e.g., “RNG.OTHER”).
- **Prohibited use:** Do not use “RNG” to label or imply affiliation with any non‑Cymos asset, product, or service. Do not register “RNG” domains, marks, or handles in a manner that confuses users about source or sponsorship.
- **Attribution line:** “RNG is the native currency of the Cymos ecosystem. © Cymos Planet. Used with permission.”
- **Revocation:** Cymos may revoke permission for misuse, user confusion, or security risk. Upon notice, promptly update tickers, metadata, and UI labels.

> Contact for listings and permissions: listings@cymos.ring (or submit an issue in this repo).

---

## 3) Exchange and wallet implementation guide
Use this section to implement RNG accurately across listings, APIs, and UI.

- **Canonical identifiers:**
  - **Symbol:** **RNG**
  - **Name:** Cymos rng
  - **Pronunciation:** “rung”
  - **Namespace (fallbacks):** RNG.CYM, CYM:RNG
- **Decimals:** 18 (recommended default)
- **Display rules:**
  - **Primary:** RNG
  - **When collision detected:** RNG.CYM (UI), CYM:RNG (API)
  - **Do not abbreviate:** Avoid ambiguous symbols (e.g., RN, RING)
- **Metadata:**
  - **Category:** Utility / Governance / Gas
  - **Description:** Native currency for fees, staking, and governance in the Cymos Ring Ledger.
  - **Tags:** cymos, native, governance, staking, utility
- **API conventions:**
  - **Pair symbols:** RNG/USD, RNG/EUR, RNG/BTC, RNG/ETH
  - **Tickers endpoint:** rng, rng_cym (fallback)
  - **Asset ID (suggested):** cymos:rng
- **Icon and assets:**
  - **Symbol mark:** RNG
  - **Monochrome glyph:** Provide SVG/PNG via this repo’s /assets directory (see LICENSE for usage).
- **Disclosure snippet (UI tooltips):**
  - “RNG (‘rung’) is Cymos’ native currency used for fees, staking, and governance on the Ring Ledger.”

---

## 4) Ledger identification and events
All `rng` movements are recorded on the Cymos Ring Ledger with ring‑aware metadata.

- **Transaction fields:**  
  - **TxID:** Immutable hash  
  - **Origin Ring:** Governance, Registry, Application, Creator, Scalar Magnitudes  
  - **Event Type:** stake, fee, reward, burn, slash, grant  
  - **Timestamp:** Network consensus time
- **Deflationary events:** A protocol‑set percentage of `rng` may be burned on magnitude writes and registry events, as determined by governance.
- **Auditing:** Indexers should retain origin ring and event type for verifiable analytics and compliance reporting.

---

## 5) Legal, brand, and licensing notice
This repository section governs use of the RNG indicator and related marks in connection with Cymos.

- **Utility asset notice:** `rng` is designed for use within the Cymos ecosystem and does not represent equity, debt, or ownership. Value may fluctuate; users should evaluate applicable laws in their jurisdiction before acquiring or using `rng`.
- **No endorsement implied:** Exchange or wallet display of RNG does not imply Cymos endorsement of third‑party services.
- **Trademark usage:** “Cymos,” “rng,” “RNG,” and “rung” are proprietary identifiers of Cymos’ native currency. Use is permitted solely to identify Cymos’ asset as described herein and subject to quality control.
- **License grant:** Non‑exclusive, non‑transferable, revocable license to use “RNG” and provided assets to identify Cymos’ native currency, conditioned on accurate, non‑misleading use and adherence to collision protocol.
- **Enforcement:** Report misuse or confusing usage to listings@cymos.planet (or via repo issue). Cymos may request corrective action, including ticker changes, disclaimers, or delisting.

---

## 6) Quick checklist for partners
- **Indicator:** Use RNG; if collision, use RNG.CYM (UI) and CYM:RNG (API).
- **Pronunciation:** “rung”.
- **Decimals:** 18.
- **Description:** “Native currency for fees, staking, and governance on the Cymos Ring Ledger.”
- **Attribution:** Include the attribution line in asset detail pages.
- **Contact logged:** listings@cymos.planet or repo issue created.

