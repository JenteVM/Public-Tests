---
title: Example Project (Front Matter)
emoji:
order: 2
description: Minimal example using description.md front matter options.
# hidden: true    # uncomment to hide from the list
# href: ./index.html  # optional: override link target
---

You can put any additional documentation here. The root index will use the
front matter above to populate the title, emoji, and description. If the
front matter description is omitted, the first non-empty paragraph is used.

## Tips: Emoji and order

- Emoji (free-form string):
  - emoji: "✨"
  - emoji: "🧑‍💻"
  - emoji: "AB"          # initials
  - emoji: "🌈🧪"        # multiple emojis
  - emoji: ""            # leave empty → default 📦
- Order (integer, lower = earlier; default 9999; ties by title):
  - order: -1  # very top
  - order: 0
  - order: 10
