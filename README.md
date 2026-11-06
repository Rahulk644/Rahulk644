# Rahul Khatri

I build the tool when it doesn't exist, and patch it when it does.

Product at Continual Engine. Before that I founded AuraX, where we built catalogue
photography on diffusion models: virtual try-on and human image generation good enough
to ship for Mensa, Aditya Birla Fashion Ventures, TMRW, SKORE and TTK Healthcare.

### Tools for agents

Agents are only as useful as the tools you hand them. So I write the tools.

- **[Appflowy-MCP-Server](https://github.com/Rahulk644/Appflowy-MCP-Server)** ·
  AppFlowy Cloud over MCP. Databases, pages, rows and blocks, through Google OAuth or a
  token. Python, FastMCP, MIT.
- **[docmost-mcp](https://github.com/Rahulk644/docmost-mcp)** ·
  Docmost over authenticated Streamable HTTP. 20 tools, default-deny on writes. Rust.
- **[Meeting-Assitant](https://github.com/Rahulk644/Meeting-Assitant)** ·
  Local-first macOS dictation and bot-free meeting capture. No bot joins your call.
  Rust, MIT.

### Patches in other people's code

- [theHarvester#2453](https://github.com/laramies/theHarvester/pull/2453) ·
  screenshot paths broke on macOS. Fixed.
- [pdfa11y#2](https://github.com/speedata/pdfa11y/pull/2) ·
  PDF/UA rule UA-10-002 was tokenising Type0 show strings by byte instead of by
  `/Encoding` width, so it flagged valid documents.
- [pdfa11y#3](https://github.com/speedata/pdfa11y/pull/3) ·
  the same rule again, one layer down: the text-state font was never restored on `Q`.

### Running elsewhere

[karmamitra](https://karmamitra.rahulkhatri.com) is a Vedic astrology AI that answers
only what its rules actually ground, and refuses the rest.
[iimbdbe](https://iimbdbe.rahulkhatri.com) is a free notes platform with on-device AI
and a 3D concept graph, because exams test recall and never test whether you saw how it
connects.

Rust, Python, TypeScript, Go, whatever the problem is written in.

Most of what I ship lives in private repos. The graph is honest; the repo list isn't.

[rahulkhatri.com](https://rahulkhatri.com) · [x](https://x.com/rahulk644) · [linkedin](https://www.linkedin.com/in/rahulk644/)
