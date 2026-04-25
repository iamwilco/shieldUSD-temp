# shieldUSD — Brand System Preview

> A standalone, monochrome, cinematic brand for shieldUSD — the first fiat-backed privacy stablecoin on the Midnight network. Issued by Moneta Digital. Tech by W3i Software.

**Version:** 0.1 · Internal review draft · 2026-04-25

---

## What's in this preview

| File | What it is |
|---|---|
| **`brand-system.html`** | The complete brand bible. Story · Mark · Wordmark · Palette · Typography · Motion · Components · Secret Layer · Voice · Co-marks. Everything that defines the system. |
| **`social-examples.html`** | Thirteen reference designs showing how the brand expresses itself across square posts, X / LinkedIn banners, blog heroes, portrait formats, and stories. Each one ships with suggested copy. |
| **`assets/shield-mark.png`** | The canonical logo. Black-on-white shield silhouette with a keyhole — protection + controlled access. |
| **`assets/shield-coin.png`** | 3D coin render of the same mark. Use for press, app icons, and product packaging. |

Both HTML files are self-contained — open them directly in a browser. Fonts load from Google Fonts (Inter Tight · Inter · JetBrains Mono).

---

## The product, in one paragraph

shieldUSD is a fiat-backed stablecoin where every transfer is private by default — sender, receiver, and amount hidden behind zero-knowledge proofs on the Midnight network — but every transaction also produces an encrypted memo readable only by a designated auditor. Compliance and confidentiality, written into the same act. Issued by Moneta Digital, built by W3i Software, designed for institutional treasury teams that can't afford to expose their balances on a public ledger but won't accept regulatory ambiguity.

---

## The three pillars (used everywhere)

1. **Private by default** — stealth UTXO commitments, shielded fees via DUST, ZK proofs on every transfer
2. **Auditable by design** — encrypted memos produced inside the proof; honest by construction
3. **Built for institutions** — co-issued through licensed entities, MiCA-aligned in the EU, Genius/Clarity-aligned in the US

---

## Locked design decisions

- **Naming:** `shieldUSD` — lowercase `s`, uppercase `USD`. Never `ShieldUSD`, `Shield USD`, `shield-usd`, or `$shieldUSD`.
- **Palette:** Pure monochrome (Ink → Paper). Two signal colors used as indicator lights only:
  - `#7DFFCE` **Decrypted** — proof valid, privacy active, audit unlocked
  - `#FF5C5C` **Compromised** — burn-timer expired, proof failed, freeze triggered
- **Typography:** Inter Tight (display, weights 200–300) · Inter (body, 300–400) · JetBrains Mono (system chrome)
- **Mark:** Shield with keyhole. Mono only. Never tinted, never gradient.
- **Motion language:** Selective Disclosure · Redacted Reveal · Privacy Bars Dissolve · Scan Line
- **Secret Layer:** Six discoverable interactions (burn timer, whisper mode, fingerprint scrambler, double-agent mode, steganography, mouse trail encryption) that make the brand *perform* privacy rather than just describe it.

---

## Voice

> Quiet, technical, certain. We never sell. We state.

**Say:** private by default · auditable by design · selective disclosure · honest by construction · confidential settlement · regulated issuer

**Don't say:** anonymous · untraceable · dark · hidden (alone) · evasion · privacy coin · military-grade · revolutionary / disruptive

---

## Co-marks

Every public surface signs off:

```
Issued by Moneta Digital · Built on Midnight · Tech by W3i Software
```

---

## What's next

This is `v0.1`. After review, we'll expand into the full skill:

- `SKILL.md` — when to invoke
- `colors_and_type.css` — exportable design tokens
- `assets/` — wordmark SVG, lockup variants, coin renders
- `ui_kits/` — component HTML reference
- `source/` — editable Figma/Affinity originals

For now: open the two HTML files, scroll through, and tell me what to refine before this gets shown to anyone outside the room.
