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
thought_status: "<% await tp.system.suggester(["inBox", "fresh", "toLink", "archive", "freezed"], ["inBox", "fresh", "toLink", "archive", "freezed"]) %>"
priority: <% await tp.system.prompt("скока приоритет") %>
---
###### <% tp.file.title %>