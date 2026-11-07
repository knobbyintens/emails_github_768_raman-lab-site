---
title: "DeltaNet: Efficient Long-Context Attention via Chunked State Routing"
venue: "NeurIPS 2025"
status: "accepted"
codeurl: "https://github.com/knobbyintens/emails_github_768_deltanet"
---

Priya Raman, Maya Chen, Daniel Okafor, Sofia Alvarez

*NeurIPS 2025 (accepted).* DeltaNet replaces dense attention with a chunked state-routing mechanism. Each sequence is split into fixed-size chunks and a learned router maintains a compressed recurrent state shared across chunks. On long-context language modelling DeltaNet matches dense attention quality while reducing KV-cache memory by 4.1x at 128K context length.
