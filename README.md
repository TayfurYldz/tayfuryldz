<div align="center">

<h1>Tayfur Yıldız</h1>

<p><code>Application Security</code> · <code>Bug Bounty</code> · <code>Security Automation</code></p>

<p>
I build small, reliable tools for authorized security research.<br />
Web application security, reconnaissance, validation, and low-noise automation.
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tayfur_Y%C4%B1ld%C4%B1z-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tayfur-y%C4%B1ld%C4%B1z-3b7820391/)
<!--
  Add a platform badge here ONLY when it links to your real public profile, e.g.:
  [![HackerOne](https://img.shields.io/badge/HackerOne-YOUR_HANDLE-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/YOUR_HANDLE)
  [![Bugcrowd](https://img.shields.io/badge/Bugcrowd-YOUR_HANDLE-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/YOUR_HANDLE)
-->

</div>

---

## About

My focus is practical application security: understanding attack surfaces, validating behavior, cutting false positives, and turning repetitive research work into tooling I can trust.

I prefer evidence over assumptions. Whether I'm chasing a security lead or fixing a bug in someone else's project, I reproduce the behavior first, work out why it happens, and verify the result before calling it solved.

## Focus areas

| Area | What that means in practice |
| --- | --- |
| **Web application security** | Attack-surface mapping, request/response analysis, and bug bounty research |
| **Security automation** | Small tools that make recon and verification repeatable |
| **Research tooling** | Less noise, and evidence kept attached to every finding |
| **Open source** | Focused fixes with regression tests in active projects |

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Marrow](https://github.com/TayfurYldz/marrow)

`Python`

Fail-closed, evidence-based HTTP request minimizer. Strips a request down to what matters without losing the behavior relevant to a finding.

</td>
<td width="50%" valign="top">

### [HeaderProof](https://github.com/TayfurYldz/headerproof)

`Python`

Low-noise active scanner for CORS, CSRF, header injection, cache poisoning, and content-spoofing leads.

</td>
</tr>
</table>

## Open source

I contribute fixes where I can reproduce the problem and cover it with a test.

- **[openlayers/openlayers](https://github.com/openlayers/openlayers)** — Fix `MouseWheelZoom` target cleanup: it now reuses the map's keyboard event handling to track the Control key instead of registering its own document listener (fixes [#17497](https://github.com/openlayers/openlayers/issues/17497)).
<!-- Add more entries as they get merged: repo, what was wrong, how you verified the fix. -->

## Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=python,bash,linux,git,github,docker&theme=dark" alt="Python, Bash, Linux, Git, GitHub and Docker" />
</p>

**Daily environment:** Kali Linux / WSL · Burp Suite · Nuclei · Nmap · ProjectDiscovery tooling · Git

## How I work

```text
Map the surface → Form a hypothesis → Reproduce → Validate → Keep the evidence
```

A result that is reproducible and defensible matters more to me than a large number of findings or changes.

---

<div align="center">
<sub>Authorized security research only. I test targets within scope and follow each program's rules.</sub>
</div>
