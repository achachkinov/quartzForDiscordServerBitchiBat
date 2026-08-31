---
id: <% tp.date.now("YYYYMMDDHHmmss") %>
created_dt: <% tp.date.now("YYYY-MM-DD HH:mm") %>
aliases: []
tags:
  - "#LEAF"
from:
related:
opposite:
next:
type:
thought_status: "<% await tp.system.suggester(["inBox", "fresh", "handling", "mature", "freezed"], ["inBox", "fresh", "handling", "mature", "freezed"]) %>"
---
###### <% tp.file.title %>