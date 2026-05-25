# analyzelog
A simple but advanced log analyzer.

install llm in 2 commands:
1. winget install llama.cpp
2. 2. llama-server -hf ggml-org/gemma-4-E2B-it-GGUF --jinja -c 0 --host 127.0.0.1 --port 8033

analyzelog.py is a multi-format log analysis tool with an interactive shell and web portal. It:
- 
Parses JSON Lines, IRC chat, and syslog formats into structured entries
- 
Summarizes logs — totals, top users/events/targets, hourly/daily histograms, error extraction
- 
Profiles users — score means, channels, flags, sentiment, activity patterns, message lengths
- 
Analyzes behavior — z-scores vs population, similarity fingerprinting, burst/session detection, response times, pattern-of-life, lifecycle stages, anomalies, change-points, churn prediction
- 
Extracts forensic artifacts — IPs, URLs, emails, file paths, hashes (MD5/SHA1/SHA256), timeline reconstruction with gaps
- 
Integrates with LLMs — behavior analysis, user comparison, clustering, forensic reports, timeline narratives, evidence extraction (with caching)
- 
Exports — HTML reports, JSON/CSV/DOT, matplotlib charts, Prometheus metrics, SQLite
- 
Provides multiple interfaces — CLI batch modes, a cmd-based REPL (~70 commands), a curses TUI dashboard, a web API server, and an HTML/JS web portal with log streaming and command execution
- 
Supports advanced features — alert rules engine, live tail/watch mode, log diffing, template mining, forecasting, recurrence/breach detection, drift monitoring, plugin system, auto-tagging
