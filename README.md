# RegexOne Practice Log

## Overview
Today spent dedicated hours to practice **regular expressions** using [RegexOne](https://regexone.com/).

The goal:
- Build stronger pattern-matching skills
- Improve ability to craft **precise YARA rules**
- Lay groundwork for efficient detection engineering in DFIR and cybersecurity contexts

---

## 📚 Lessons & Exercises Completed

1. Introduction
2. The Dot (.)
3. Matching Specific Characters
4. Excluding Specific Characters
5. Character Ranges
6. Matching Repeated Characters
7. Kleene Operators
8. Optional Characters
9. Matching Whitespaces
10. Anchors (^…$)
11. Capture Groups
12. Nested Groups
13. More Group Work
14. Conditional Matching
15. Other Special Characters

### Key Patterns Learned
| Pattern | Purpose |
|---------|---------|
| `\d` | Match any digit |
| `\w` | Match any alphanumeric |
| `[abc]` | Match specific letters |
| `[^abc]` | Match anything except a, b, c |
| `{m,n}` | Match between m and n repetitions |
| `(abc|def)` | Match either abc or def |
| `^pattern$` | Match entire line exactly |

---

## Takeaways
- Regex is **foundational** to detection engineering.
- Many YARA rules can be elevated by replacing literal strings with **regex-based conditions**.
- Escaping matters (`\.` vs `.`) — a single missing backslash can change everything.
- Regex strengthens both **defensive filtering** and **offensive payload crafting**.
  
---

## Credits & Acknowledgement
This work was **based entirely on exercises provided by [RegexOne](https://regexone.com/)**.  
They provide **free, high-quality learning resources** for anyone to master regular expressions.

If you found this useful, please consider **donating** to such free educational platforms so they can keep creating accessible knowledge for everyone.

---

**#700DaysOfSkill**
