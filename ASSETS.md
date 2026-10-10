# metaCAMPUS assets (on-chain record)

Operational notes for Algorand assets associated with metaCAMPUS / EQ2 direction.
This file is the **ledger of issued pilot assets**, not a governance charter.

**Labeling rule:** TestNet pilot / vanity ASA only. Do **not** describe these units as EQ2 equity, governance tokens, or securities.

---

## TestNet — `mC` (vanity ASA)

| Field | Value |
|---|---|
| **Network** | Algorand TestNet (`testnet-v1.0`, genesis `SGO1GKSzyE7IEPItTxCByw9x8FmnrCDexi9/cOUJOiI=`) |
| **ASA ID** | **`773957514`** |
| **Create tx** | `LHXS3DYXJWTKZFZPYORZWVJDTMC5IAY2X35R6Z3PTU4OLOE3DKNA` |
| **Confirmed round** | `68104848` |
| **Name** | `metaCAMPUS mC Token` |
| **Unit name** | `mC` |
| **Total supply** | `1_000_000` (base units) |
| **Decimals** | `0` |
| **Default frozen** | `false` |
| **URL** | https://metacampus-on-algorand.grok.me |
| **Creator** | `I4ZBH6RZRTFQN6DSTYJESIGK4VPSMDTXSXJEYEVBADVDQFSOQR4OV55BVE` |
| **Manager** | `I4ZBH6RZRTFQN6DSTYJESIGK4VPSMDTXSXJEYEVBADVDQFSOQR4OV55BVE` |
| **Reserve** | `I4ZBH6RZRTFQN6DSTYJESIGK4VPSMDTXSXJEYEVBADVDQFSOQR4OV55BVE` |
| **Freeze** | `I4ZBH6RZRTFQN6DSTYJESIGK4VPSMDTXSXJEYEVBADVDQFSOQR4OV55BVE` |
| **Clawback** | `I4ZBH6RZRTFQN6DSTYJESIGK4VPSMDTXSXJEYEVBADVDQFSOQR4OV55BVE` |
| **Explorer** | https://lora.algokit.io/testnet/asset/773957514 |
| **Minted** | 2026-10-09 |

### Scope

- Simple **AssetConfig** create on TestNet.
- Freeze and clawback **enabled** on the control address above.
- Creator held the full supply at mint; other accounts must **opt in** before receiving `mC`.
- Same address string is used as MainNet x402 `payTo` for credential verify; **TestNet balances and assets are separate** from MainNet.

### Explicit non-goals

- Not MainNet.
- Not EQ2 DAO governance, voting, or derivative tokenomics.
- Not a replacement for USDC in the x402 Global Challenge path (MainNet USDC ASA `31566704`).
- Not marketed as a transferable security.

### Related

- Product page: https://metacampus-on-algorand.grok.me
- x402 paid verify (MainNet USDC): https://github.com/metacampus-org/metacampus-x402-verify
- Local mint checklist (project artifacts): `mc-asa-testnet-mint-checklist.md`

---

## MainNet

No metaCAMPUS-issued fungible ASA on MainNet as of 2026-10-09.

Challenge / agent payments use **Circle USDC** ASA `31566704` via GoPlausible facilitator, not `mC`.
