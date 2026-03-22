⚡ FastCode
Up to 4x faster AI coding. Local + Cloud. From €1/month.
FastCode is an optimized fork of OpenCode — a terminal-based AI coding tool that's been rewritten for speed. It works with cloud models (Claude, GPT, Gemini) or runs fully offline with Qwen 3 Coder 30B via Ollama.
🌐 Website: fastcode-dev.com
***Benchmarks
Averaged across 10 identical runs. Same task, same model (Claude Opus), same machine.
|                    | FastCode   | OpenCode | Claude Code |
|--------------------|-----------|----------|-------------|
| Avg. time      | 93s   | 250s     | 153s        |
| Tool calls     | 23    | 43       | 41          |
| Tokens used    | 289k  | 605k     | 1.80M       |
| File reads     | ~5    | ~31      | ~22         |
| vs OpenCode    | 2.7x faster | —  | 1.6x faster |
| Tokens vs Claude | 6.2x fewer | 3x fewer | — |
Local model — Qwen 3 Coder 30B
| Metric       | Result        |
|-------------|---------------|
| Task time   | 179–229s      |
| Tool calls  | 8–12          |
| File reads  | 5–6           |
| Output      | 225–311 words |
> On "up to 4x": The raw benchmark shows 2.7x faster than OpenCode and 6.2x fewer tokens than Claude Code. The remaining gains come from voice input, fast-apply edits, quick actions, and the OIDX context engine that reduces redundant file reads. In real daily use, the compounded improvement reaches the 4x range. We show the raw numbers because we believe in transparency.
What makes it different
2.7x faster than OpenCode, 1.6x faster than Claude Code (benchmarked)
6.2x fewer tokens than Claude Code — lower API costs
Local AI — runs Qwen 3 Coder 30B via Ollama, fully offline, your code never leaves your machine
Cloud models — Claude, GPT-4, Gemini, any OpenAI-compatible API
Terminal-native — no Electron, no browser, no IDE plugin. Just your terminal
OIDX context engine — smarter file indexing, fewer redundant reads
Voice input — speak your instructions
Fast-apply — direct file edits without diff roundtrips
Work stats — track your AI-assisted productivity
Code scoring — quality and security checks built in
Install
curl -fsSL https://fastcode-dev.com/install.sh | sh
Activate
fastcode activate --key FC-XXXX-XXXX-XXXX
Usage
fastcode
That's it. Describe what you want to build and FastCode handles the rest.
Local AI setup
Install Ollama
Pull the model: ollama pull qwen3-coder:30b
Run FastCode — it detects Ollama automatically
No API keys needed. No internet required. Full privacy.
Pricing
| Plan     | Price      | Details                          |
|----------|-----------|----------------------------------|
| Monthly  | €1/mo | Cancel anytime. All features.    |
| Lifetime | €50   | One payment. Yours forever.      |
👉 Get FastCode
Requirements
macOS or Linux (Windows coming soon)
For local AI: 16GB+ RAM recommended (M-series Mac or GPU with 24GB+ VRAM)
For cloud: any API key (Anthropic, OpenAI, Google, etc.)
Support
Email: support@fastcode-dev.com
Issues: GitHub Issues
Built on
FastCode is a fork of OpenCode, licensed under MIT. Our optimizations, OIDX engine, and proprietary features are what you're paying for. The original OpenCode remains free and open source.
License
Proprietary. See Terms of Service.
Based on OpenCode (MIT License).
