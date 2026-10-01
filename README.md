> **Experimental. Not advice.** [DISCLAIMER.md](DISCLAIMER.md)

# tkaswallet build and bot

Testnet-10 only. Grok Build and Grok Bot each have one big wallet. Each wallet funds that side's own smaller wallets. The two treasuries are not the same wallet, and neither side spends the other side's coins.

| Who | Treasury | Address |
| --- | --- | --- |
| Grok Build | Build wallet | `kaspatest:qp4jge54eztxewf8r53rtjdvxakmatsu6tjd0nn9sjhgvzxknsfvjvmwurqhd` |
| Grok Bot | Bot wallet | `kaspatest:qzffl5xy9np46gkttyuftqnv2w04pr8g3wsp7c3vv8se3txtelx6q7c0v0ldx` |

## Grok Build

`kaspatest:qp4jge54eztxewf8r53rtjdvxakmatsu6tjd0nn9sjhgvzxknsfvjvmwurqhd`

This is Grok Build's own Testnet-10 wallet. Grok Build uses it to fund Grok Build test wallets. The key stays off this GitHub.

[tn10.kaspa.stream](https://tn10.kaspa.stream/addresses/kaspatest:qp4jge54eztxewf8r53rtjdvxakmatsu6tjd0nn9sjhgvzxknsfvjvmwurqhd)

Opening receipts, read from synced public kaspad 2.1.0 `vector-10.kaspa.green` at 2026-10-01 19:26 +02:00. This is the funding Grok Bot sent into the Build wallet. It is not a live balance.

| Transaction | Output | tKAS |
| --- | --- | --- |
| `4f3c4166ccc62fa40163be14893f8327530b45ba2506ff8a2e306641fe918c8b` | 0 | 105,258.94270693 |
| `233874db1835172edcc4982b946bc059ebaf03f076933803d5cd3bc39f3ebffd` | 0 | 61,131.34960715 |
| Total at that read | | 166,390.29231408 |

## Grok Bot

`kaspatest:qzffl5xy9np46gkttyuftqnv2w04pr8g3wsp7c3vv8se3txtelx6q7c0v0ldx`

This is Grok Bot's own Testnet-10 wallet. Mining rewards are paid here. Grok Bot uses it to fund Grok Bot wallets. The key stays off this GitHub.

[tn10.kaspa.stream](https://tn10.kaspa.stream/addresses/kaspatest:qzffl5xy9np46gkttyuftqnv2w04pr8g3wsp7c3vv8se3txtelx6q7c0v0ldx)

## Rules

- Testnet-10 only. Addresses stay `kaspatest:`. Mainnet stays out.
- This repo names the two treasuries. It does not hold a seed, a private key, or a wallet file.
- A figure on this page is the receipt from the time it was read. A synced Testnet-10 node has the current balance.

Intentions are good; thought process is questionable. STP remains delusional. Si vis pacem, para bellum.
