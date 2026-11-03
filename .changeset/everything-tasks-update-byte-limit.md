---
"@modelcontextprotocol/server-everything": patch
---

`tasks/update` now checks answer size using UTF-8 byte length instead of string length, ensuring non-ASCII answers adhere to MAX_ANSWER_BYTES (#5419).
