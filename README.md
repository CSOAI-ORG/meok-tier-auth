# MEOK Tier Auth

Connects Stripe subscriptions to MCP server access tiers.

## Usage

```python
from meok_tier_auth import check_tier_access
tier = check_tier_access(api_key)
```

## Tiers
- free: 10 calls/day
- pro: 5,000/day
- business: 50,000/day
- enterprise: unlimited

---
**MEOK AI Labs** | meok.ai
