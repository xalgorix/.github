# Xalgorix

> Autonomous AI penetration testing platform. Orchestrating 70+ security tools for exploit-verified pentesting & automated security audits.

---

### Mission & Capabilities

Xalgorix is designed to automate complex security assessments by combining LLM-powered reasoning with industry-standard security tools.

- Autonomous AI Pentesting: Intelligent agent-driven target analysis and exploitation.
- 70+ Security Tools Orchestrated: Seamless integration with Nmap, Metasploit, Gobuster, and more.
- Exploit Verification: Real validation of vulnerabilities to eliminate false positives.
- Automated Audits: Comprehensive reporting and vulnerability mapping.

---

### Quick Links

* [Official Website](https://www.xalgorix.com/?utm_source=github&utm_medium=org_profile&utm_campaign=oss_to_cloud&utm_content=quick_links)
* [Documentation](https://docs.xalgorix.com/?utm_source=github&utm_medium=org_profile&utm_campaign=oss_docs&utm_content=quick_links)
* [Open-source engine (Apache-2.0)](https://github.com/xalgorix/xalgorix)
* [Free security review on every pull request (GitHub App)](https://github.com/apps/xalgorix)
* [Support the Project (GitHub Sponsors)](https://github.com/sponsors/xalgord)
* [Medium Blog / Writeups](https://xalgord.medium.com)

---

### Quick Start

Run the self-hosted dashboard with Docker:

```bash
docker run --rm -p 9137:9137 --privileged -v xalgorix-data:/data xalgord/xalgorix:latest
```

Then open `http://localhost:9137` and add your LLM provider under **Settings → LLM** (local Ollama works too). The full install guide, including the one-line installer for Linux and macOS, is in the [main repository](https://github.com/xalgorix/xalgorix#-quick-start).

Prefer zero setup? [Xalgorix Cloud](https://www.xalgorix.com/signup?utm_source=github&utm_medium=org_profile&utm_campaign=oss_to_cloud&utm_content=quick_start) runs the same engine in your browser, with no install or LLM key.

Only scan systems you own or have explicit permission to test.
