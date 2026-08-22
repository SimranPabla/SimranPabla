# Simranjit Singh

Computer Science student at the University of Alberta building software at the intersection of **software engineering, cybersecurity, AI systems, and agent reliability**.

I focus on turning ambiguous technical problems into systems with explicit boundaries, observable evidence, and practical failure handling. My current work spans AI-agent integrity, API/data automation, network tooling, and media-processing applications.

## Selected Projects

### [Agent Review Control (ARC)](https://github.com/SimranPabla/agent-review-control)
Upstream integrity and reliability architecture for AI coding agents built around **Contract + Evidence + Verdict**.

- Reconstructs project state from canonical artifacts rather than treating chat history as authoritative.
- Freezes task scope, acceptance criteria, risk boundaries, and required evidence before execution.
- Separates upstream contract/evidence integrity from downstream execution-governance systems.
- Public repository contains architecture and dogfood evidence; active deterministic implementation work remains private.

### [CyberFlow Sentinel](https://github.com/SimranPabla/Cybersecurity-Articles-Storytelling-Videos)
Production-operated AI/data/API automation pipeline for cybersecurity content processing.

- Processes **50+ cybersecurity articles per day**.
- Reduced manual workflow effort by approximately **90%**.
- Supports published content reaching approximately **10,000 weekly viewers**.
- Integrates n8n, OpenAI API, Airtable, Pictory API, REST APIs, Docker, Linux, DigitalOcean, Apache, TLS, and social-platform APIs.

### [Packet Sniffer](https://github.com/SimranPabla/Packet-Sniffer)
Python + Scapy CLI for live network packet capture and inspection.

- Supports summary/detail output and BPF capture filters.
- Streams captured text to stdout or an output file.
- Documents privilege requirements, limitations, and responsible-use boundaries.

### [VideoGen Pro](https://github.com/SimranPabla/VideoGen-Pro)
Flask media-processing prototype using Whisper and MoviePy/FFmpeg.

- Image/audio workflow with drag-and-drop ordering.
- Whisper transcription with CPU/CUDA selection through PyTorch.
- Background H.264/AAC rendering with Server-Sent Events progress reporting.
- Explicitly documents current single-process reliability and security limitations.

## Open Source

- **OpenClaw** — [merged PR #111534](https://github.com/openclaw/openclaw/pull/111534): fixed Linux gateway restart behavior when a process inherits cross-user D-Bus state, with regression tests and real systemd validation.
- **Google CAGE** — [issue #53](https://github.com/google/cybernetic-agent-governance-engine/issues/53): identified a governance-boundary inconsistency that collapsed human-review semantics into `DEFER`; the issue was closed after the project resolved the identified behavior.

## Technical Areas

**Programming:** Python, TypeScript/JavaScript, SQL, Bash/Shell  
**Software:** REST APIs, Flask, Git/GitHub, Docker, n8n, FFmpeg  
**AI systems:** OpenAI API, Whisper, LLM workflows, agent reliability, evidence/contract integrity  
**Systems:** Linux/Unix, Apache, Windows Server  
**Networking & security:** TCP/IP, DNS, DHCP, Active Directory, Scapy, firewalls

## Certifications

CompTIA Security+ · ISC2 Certified in Cybersecurity (CC) · EC-Council CCT · CompTIA A+

## Links

- Portfolio: [simranpabla.com](https://simranpabla.com)
- LinkedIn: [linkedin.com/in/simranjit-singh-pabla](https://www.linkedin.com/in/simranjit-singh-pabla/)
