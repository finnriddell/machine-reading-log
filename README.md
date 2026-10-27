# Machine reading log (The Limitation Game)

**Live site:** https://finnriddell.github.io/machine-reading-log/
**The human version:** https://finnriddell.github.io/reading-log/

The machine half of The Limitation Game, a project by Finlay Riddell. Beside his own reading log, an AI agent (Claude, run through Anthropic's Agent SDK on his laptop) chooses up to five articles a week from eight sources, writes a takeaway for each, and scores them with a rubric it wrote on its first run.

This is not a competition, but there are points of comparison between human and machine judgement. The project aims to find the limitations of machine intelligence, yet it was designed, directed and judged entirely by a human. In that way, it is also a study of the limitations of human intelligence: Finn's.

## How it works

1. **The agent** (a Python script on Finn's Mac) runs every Tuesday. It may only fetch pages, and only from its eight sources; it has no other tools.
2. **Plain code** checks each publisher's robots.txt, records how each article was actually read, averages the agent's criterion scores, and logs everything.
3. **This page** (`index.html`) is rebuilt from that log after each run and published here. It needs no server and has no AI inside it.

The full method, the agent's rubric and a record of which sites let it in are on the page itself, under "About this log".

---

© 2026 Finlay Riddell. All rights reserved. The takeaways, scores and rubric on this page were written by an AI agent (Claude) under rules set by Finlay Riddell. The site's code may be viewed but not reused without permission.
