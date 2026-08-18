# Weicheng (Troy) Wang

Product-minded software engineer building AI-native mobile experiences and reliable backend systems.

I care about the parts of AI products that live beyond the demo: trustworthy context handling, structured outputs, deterministic fallbacks, privacy boundaries, testable architecture, and a calm user experience.

## Current focus

### Lumi — privacy-aware AI life assistant

Lumi is an iOS assistant that brings calendars, reminders, weather, user-approved memory, and conversational planning into one daily workflow.

I lead the product and engineering work across:

- a native **SwiftUI** client using EventKit, WeatherKit, Core Location, Speech, and UserNotifications;
- a **FastAPI** backend with strict Pydantic contracts, Supabase authentication and persistence, and provider abstractions;
- structured calendar/task mutations with explicit review before user data changes;
- deterministic scheduling, fallback, and cache paths that keep the product useful when AI is unavailable;
- automated coverage across iOS domain logic, API contracts, repositories, authentication, and provider failure modes (`817` iOS tests and `286` backend tests in the current verified build).

The source repository is private during active product development and is available for interview review.

## Selected work

### [Parallel Stencil Benchmark](https://github.com/Troy08/parallel-stencil-task)

OpenMP parallelization and strong-scaling analysis of a 2D Jacobi stencil, including reproducible benchmarks, byte-level correctness checks, bandwidth analysis, and an explanation of memory-bound scaling behavior on Apple silicon.

### [Error-Bounded Scientific Compression](https://github.com/Troy08/sz3-compression-task)

A reproducible SZ3 rate–distortion study on Hurricane ISABEL data with error-bound sweeps, independent PSNR verification, compression metrics, and generated analysis plots.

### [Case Management Assessment Platform](https://github.com/Troy08/CommonAssessmentTool)

A team-built Python service for case management and intervention analysis, with authenticated CRUD APIs, data processing, automated tests, and a separate web client.

## Engineering toolkit

`Swift` · `SwiftUI` · `Python` · `FastAPI` · `Supabase/PostgreSQL` · `LLM systems` · `C/OpenMP` · `Flutter` · `Vue`

## How I work

- Start with the user workflow and define what must remain deterministic.
- Keep external providers behind small, replaceable interfaces.
- Validate AI output as untrusted data before it reaches product state.
- Prefer reproducible experiments and measurable results over unsupported claims.
- Use automated tests to protect domain rules and integration boundaries.
