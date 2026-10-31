# Weicheng (Troy) Wang

**Incoming PhD Student @ George Mason University | AI Security & Memory Forensics | Software Engineer**

I'm an incoming PhD student in Information Science and Technology at George Mason University, beginning in Spring 2027.

My research interests include AI Security, Memory Forensics, LLM Security, and Trustworthy AI. I am particularly interested in understanding the security implications of AI systems through runtime analysis and forensic reconstruction.

Alongside research, I have a background in software engineering, AI-powered applications, and scalable backend development.

## Current focus

### LLM Watermark Security & Memory Forensics

*Preliminary PhD Research - George Mason University*

Exploring the security implications of LLM watermark state exposure in runtime memory.

Current research directions include:

- Investigating the recovery of watermark configurations from offline memory snapshots.
- Exploring source-guided, symbol-independent memory reconstruction.
- Evaluating the security implications of recovered watermark states.
- Studying watermark behavior reproduction across different language models.

**Status:** Preliminary research and feasibility investigation.

### Lumi - Privacy-Aware AI Life Assistant

Building an AI-native iOS assistant focused on personal productivity, privacy, and reliable automation.

- iOS: SwiftUI, EventKit, WeatherKit, Core Location
- Backend: Python, FastAPI, Supabase, PostgreSQL
- AI: LLM integration, structured outputs, context management
- Engineering: API design, testing, authentication, and reliable fallback systems

Lumi is an iOS assistant that brings calendars, reminders, weather, user-approved memory, and conversational planning into one daily workflow.

I lead the product and engineering work across:

- a native **SwiftUI** client using EventKit, WeatherKit, Core Location, Speech, and UserNotifications;
- a **FastAPI** backend with strict Pydantic contracts, Supabase authentication and persistence, and provider abstractions;
- structured calendar/task mutations with explicit review before user data changes;
- deterministic scheduling, fallback, and cache paths that keep the product useful when AI is unavailable;
- automated coverage across iOS domain logic, API contracts, repositories, authentication, and provider failure modes (`817` iOS tests and `286` backend tests in the current verified build).

The source repository is private during active product development and is available for interview review.

## Research interests

AI Security · Memory Forensics · LLM Security · Trustworthy AI · Runtime Analysis · Digital Forensics

## Selected work

### [Parallel Stencil Benchmark](https://github.com/Troy08/parallel-stencil-task)

OpenMP parallelization and strong-scaling analysis of a 2D Jacobi stencil, including reproducible benchmarks, byte-level correctness checks, bandwidth analysis, and an explanation of memory-bound scaling behavior on Apple silicon.

### [Error-Bounded Scientific Compression](https://github.com/Troy08/sz3-compression-task)

A reproducible SZ3 rate–distortion study on Hurricane ISABEL data with error-bound sweeps, independent PSNR verification, compression metrics, and generated analysis plots.

## Engineering toolkit

`Swift` · `SwiftUI` · `Python` · `FastAPI` · `Supabase/PostgreSQL` · `LLM systems` · `C/OpenMP`

## How I work

- Start with the user workflow and define what must remain deterministic.
- Keep external providers behind small, replaceable interfaces.
- Validate AI output as untrusted data before it reaches product state.
- Prefer reproducible experiments and measurable results over unsupported claims.
- Use automated tests to protect domain rules and integration boundaries.
