# Surge Rules

Personal Surge external rule sets.

## Rule sets

| File | Suggested policy | Scope |
| --- | --- | --- |
| `rules/us-sensitive.list` | `家宽` | Broad US sensitive/account services excluding video/download-heavy services |
| `rules/us-banks.list` | `家宽` | Focused US banks, brokerages, cards and payments |
| `rules/us-finance.list` | `家宽` | US banks, cards, payments, US mobile/account services |
| `rules/binance.list` | `DIRECT` or selected crypto policy | Binance and related services |
| `rules/japan-services.list` | `Japan` | ANA, Toyota Wallet, LINE |
| `rules/monzo.list` | `United Kingdom` | Monzo UK |
| `rules/pikpak.list` | `PikPak` | PikPak |

Use jsDelivr links in Surge for better availability:

```ini
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/us-sensitive.list,家宽
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/us-finance.list,家宽
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/us-banks.list,家宽
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/binance.list,DIRECT
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/japan-services.list,Japan
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/monzo.list,"United Kingdom"
RULE-SET,https://cdn.jsdelivr.net/gh/a1655049627/surge-rules@main/rules/pikpak.list,PikPak
```
