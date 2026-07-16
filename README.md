# Roadmaps

Interactive, roadmap.sh-style learning roadmaps rendered as single-file HTML pages.

## FPGA Front-End Engineer — Zero to Expert

**File:** [`fpga-frontend-roadmap.html`](fpga-frontend-roadmap.html) — open it directly in any browser (no build step, no dependencies).

A complete zero-to-expert path for FPGA front-end engineering covering **design, verification, and validation**:

| Stage | Focus | Suggested duration |
|---|---|---|
| 0 | Foundations — digital logic, computer architecture, Linux/Git | 4–8 weeks |
| 1 | HDL fundamentals — Verilog/SystemVerilog RTL, testbenches | 6–10 weeks |
| 2 | FPGA architecture — LUTs, BRAM, DSP, clocking, I/O, vendors | 3–5 weeks |
| 3 | Design flow — synthesis, implementation, constraints, Tcl, IP | 4–6 weeks |
| 4 | Timing, CDC & reset — STA, metastability, async FIFOs, closure | 6–8 weeks |
| 5 | Verification — plans, SV/OOP, coverage, UVM, SVA, formal, cocotb | 8–12 weeks |
| 6 | Validation & lab bring-up — ILA, board bring-up SOP, HW/SW co-debug | 4–6 weeks |
| 7 | Interfaces — UART/SPI/I2C, AXI, DDR, SerDes, PCIe, Ethernet, video | 6–10 weeks |
| 8 | SoC FPGAs, HLS & advanced — Zynq, embedded Linux, DSP, PR, security, safety | 8–12 weeks |
| 9 | Expert practice — sign-off SOPs, lint/CDC tooling, CI/CD, reviews, career | ongoing |

### Features

- **74 clickable topics**, each with:
  - What to learn (concrete objectives)
  - Curated references (books, papers, docs, tools, tutorials)
  - Hands-on exercises and projects
  - **Corner cases & gotchas** (the bugs that bite in the field)
  - **Best practices / SOPs** (how professionals actually work)
- Topics tagged **core**, **advanced/specialization**, or **optional**
- Per-stage milestones ("you're ready to move on when…")
- Progress tracking with "Mark as done" (persisted in browser localStorage)
- Light/dark theme aware, mobile responsive, fully self-contained (no external assets)
