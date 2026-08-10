## David Hahn

**Computer Science graduate — University of Auckland.** Auckland, New Zealand.

Six years of C# and a habit of finishing things: an 89,000-line game codebase in its fourth year,
a custom 2D engine underneath the next one, and a search-and-rescue system taken to open water
with Auckland Police.

**Open to software engineering roles in Auckland.**

### Selected work

**[SAR Datums](https://github.com/dvhahn/sar-datums) — drift prediction for Auckland Police Search & Rescue**
`Python` · `Flask` · `PostgreSQL/PostGIS` · `MapLibre GL` · `AWS`

Capstone project for a real client, replacing an 18-year-old Excel and VBA tool. I was project
manager and lead developer on a five-person team, working across the stack: the PostGIS schema and
the import pipeline behind a 52-million-row tidal vector dataset, the leeway and tidal-current
drift model, the Flask API, and the map interface operators work from. Ported the legacy VBA model
to Python and verified it against the original across the full input range, documenting every
divergence before release. Selected by the client for a real-water field test in June 2026 and
demonstrated to Coastguard New Zealand.

**Long-horizon game project** — solo, 2022–present
`C#` · `Unity`

89,000 lines, four years, one person. Architecture, release pipeline, version control, asset
pipeline and project management all mine. Entered beta in Q1 2026. Product details stay private
until release; the engineering is open to discussion.

**PixelCore — custom 2D engine** — solo
`C#` · `FNA` · `Dear ImGui`

A purpose-built top-down engine for the next project: Y-sorted renderer, entity and scene model,
axis-separated physics, JSON scene serialization, and an in-game editor built on Dear ImGui, with
a lighting and post-processing stack on top. Written to be understood rather than reused — every
design decision is recorded with the argument behind it.

### Also public

| | | |
|---|---|---|
| [Censor](https://github.com/dvhahn/censor) | Chrome extension, [live on the Chrome Web Store](https://chromewebstore.google.com/detail/censor-blur-sensitive-inf/dcpkpnfgkpapfhdpgmlggpmagmmhomde) — click or drag to blur anything on screen before a screen share. Manifest V3, zero network calls | `JavaScript` |
| [ScriptPad](https://github.com/dvhahn/ScriptPad) | Markdown editor for macOS built on a hand-written `NSTextView` subclass rather than stock SwiftUI — live syntax highlighting, focus and typewriter modes, Safari-style tabs, IME-safe shortcuts | `Swift` · `SwiftUI` · `AppKit` |
| [Flour &amp; Flames](https://github.com/dvhahn/recipe-portal) | Recipe portal whose domain logic runs against either an in-memory CSV store or SQLAlchemy/SQLite, switched by one config flag. On a four-person team I built search, the home and featured pages, and the database and end-to-end test suites (COMPSCI 235, A+) | `Python` · `Flask` · `SQLAlchemy` |

### Stack

| | |
|---|---|
| **Languages** | C# (advanced), Python, JavaScript, Java, Swift |
| **Backend** | Flask, PostgreSQL, PostGIS, SQLite, REST API design |
| **Frontend** | React, JavaScript, HTML, CSS, SwiftUI |
| **Tools** | Git, AWS, Unity, FNA, Netlify, Figma, Linear |
| **AI tooling** | Daily user of Claude Code. Architecture, direction and review stay with me. |
