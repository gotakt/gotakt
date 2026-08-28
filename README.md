## Marwan Saleh

Software for small companies that depend on it — Hannover, Germany.

I run **[gotakt](https://gotakt.de)**. Most of what I ship is a working system
for one business rather than a library: a time clock on a tablet by the door, a
proof-of-service portal a cleaning company hands to its customers, a workflow
that replaces a folder of PDFs and a shared spreadsheet.

That work comes with a particular constraint. When it breaks, somebody's hours
are wrong, or an invoice cannot be issued that week. Not an outage — a person
with a real problem. It changes what "done" means.

### How I build

**A small stack, and few dependencies.** Every dependency is something I have to
understand on the day it fails, usually while somebody is waiting.

**Plain language in the interface.** An error says what actually happened and
what to do next. "Failed to fetch" is a sentence for me, not for the person at
the front desk.

**Tests where the money is.** Not a coverage number — tests around the parts
that would cost somebody real money if they were quietly wrong. A test that
proves nothing is worse than no test, because it looks like proof.

**Measured, not assumed.** Before a document claims a system does something, I
check it against the running system. Most of the bugs worth finding live in the
gap between what software does and what its documentation says about it.

### Selected work

**[TÜV Prüfstelle Pro](https://github.com/gotakt/tuv-workflow-web)**
Management system for vehicle inspection centres: scheduling, vehicles, defect
catalogue, statistics and printable inspection reports. React/Vite against an
Express API and MariaDB.

**[gotakt-claude-dashboard](https://github.com/gotakt/gotakt-claude-dashboard)**
A local control panel for parallel Claude Code sessions. It reads the
transcripts Claude Code already writes and shows which session is waiting for
you, which one stopped mid-turn, and what each has cost. State comes from Claude
Code hooks with a documented fallback for when they are unavailable. One file,
no dependencies.

**[autobahn-strava](https://github.com/gotakt/autobahn-strava)**
Strava for Autobahn drives — except the score rewards the best *legal* drive
rather than the fastest one.

Client work lives in private repositories.

### Stack

| | |
|---|---|
| **Frontend** | React · Vite · Next.js · Astro · Tailwind |
| **Backend** | Node · Express · Firebase · Supabase / Postgres · MariaDB |
| **Testing** | Vitest · Playwright · emulator-based security-rule tests |
| **Also** | Python · Tauri · Capacitor |

### Contact

[kontakt@gotakt.de](mailto:kontakt@gotakt.de) · [gotakt.de](https://gotakt.de)
