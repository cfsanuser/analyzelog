# analyzelog
A simple but advanced log analyzer.

install llm in 2 commands:
1. winget install llama.cpp
    or brew install llama.cpp
2. llama-server -hf ggml-org/gemma-4-E2B-it-GGUF --jinja -c 0 --host 127.0.0.1 --port 8033

analyzelog.py loaded — 13,147 lines. It's a comprehensive log analysis toolkit with:
Core parsing — Handles JSON Lines (AI scores with heu/bino/cls/llama fields), IRC chat, syslog, BSD syslog, and generic timestamped formats.
Analysis features:
- Report generation with top users, events, targets, hourly/daily histograms, error detection
- User profiling: score means, activity patterns, sentiment analysis, topic/keyword extraction
- LLM integration: behavior analysis, user comparison, anomaly explanation, forensic reports, threat assessment, bot detection, deep behavioral profiling, social dynamics, incident timeline reconstruction
- Statistical: Z-scores, percentiles, histograms, anomaly detection, change-point detection, forecast activity
- Interaction: reply graphs, edge networks, session detection, response times, co-occurrence, burst detection
- Forensics: entity extraction (IPs/URLs/hashes/emails), log tamper detection, timeline gaps, sequence mining
- Export: CSV, JSON, GraphML, DOT, SQLite, HTML reports, Prometheus metrics
- Interactive shell, curses dashboard, web portal (HTML/JS), watch/tail mode, command chaining/aliases/macros/presets
