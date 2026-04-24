# News Slot Format (v1)

## Slot files
- `news/BOB_EVENT_SLOT_1.txt`
- `news/BOB_EVENT_SLOT_2.txt`

## Value format
`YYYY-MM-DD|HH:MM|ALIAS|IMPACT`

Example:
`2026-04-22|20:00|FED|high`

## Empty value
`NONE`

## Notes
- Up to 2 relevant following events of the day are exported.
- Event aliases are used for compact display in Pine HUDs.
- Event visibility may remain active for a configured post-event hold window.
