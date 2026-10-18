# linux-sm61x5

Kernel tree for Qualcomm SM6125 (Snapdragon 665) devices: Xiaomi Mi A3 (laurel_sprout), Mi 9 Lite, Redmi Note 8/8T and related.

## Branches
- `upstream` — bot-synced mirror of [codeberg.org/sm61x5-mainline/linux](https://codeberg.org/sm61x5-mainline/linux). Never commit here manually.
- `omnipha` — our patches, rebased onto upstream tags by bot. Contributions via PR against this branch.
- `main` — this documentation only.

## Kernel policy
Upstream activity is tracked in [UPSTREAM.md](UPSTREAM.md). While upstream is active, Omnipha builds reference it and we push patches upstream when possible. If upstream goes inactive, `omnipha` becomes the maintained source of truth.

## License
GPL-2.0-only, same as upstream Linux.
