<h1 style="font-size: 30px;"><b>🪟 Windows Enumeration & Baseline Project</b></h1>

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)

This repository provides a simple, organized collection of PowerShell commands used for:

- Inspecting running processes, network activity, and registry auto-start entries  
- Building a clean Windows baseline for comparison  
- Performing differential analysis before and after incidents  

The goal is to give analysts a lightweight, browser-friendly reference they can use during investigations, lab work, or system reviews — without needing complex tools or large frameworks.

All content is kept simple and flat:

- <b>commands.md</b> — Enumeration commands for processes, network connections, and registry auto-start keys  
- <b>baseline.md</b> — Baseline creation steps and differential analysis workflow  

---

<h2 style="font-size: 24px;"><b>📚 Table of Contents</b></h2>

1. <a href="#how-to-use-this-repo">How to Use This Repo</a>  
2. <a href="#repository-structure">Repository Structure</a>  
3. <a href="#files-included">Files Included</a>  

---

<h2 id="how-to-use-this-repo" style="font-size: 24px;"><b>🧭 How to Use This Repo</b></h2>

This project is designed to be used directly from the GitHub web interface or copied into your own environment.

<h3 style="font-size: 20px;"><b>🛠️ Use it for:</b></h3>

- Building a Windows baseline before an incident  
- Comparing system state after an incident  
- Running quick enumeration commands during triage  
- Teaching or documenting DFIR workflows  
- Creating repeatable, modular detection engineering notes  

<h3 style="font-size: 20px;"><b>📌 How to work with it:</b></h3>

1. Open the <b>Enumeration commands</b> folder to run enumeration commands.  
2. Open the <b>Baseline creation + differential analysis</b> folder to generate baseline files and perform comparisons.  
3. Use the comparison steps to identify differences.  
4. Extend or modify the files as needed — everything is plain Markdown.  

---

<h2 id="repository-structure" style="font-size: 24px;"><b>📁 Repository Structure</b></h2>

<b>🔍 Enumeration</b>  
   ↳ (Enumeration commands folder)

⬇️

<b>📊 Baseline Creation Phase</b>  
   ↳ (Baseline creation + differential analysis folder)

⬇️

<b>🧪 Differential Analysis</b>  
   ↳ Compare baseline vs current system state

---

<h2 id="files-included" style="font-size: 24px;"><b>📄 Files Included</b></h2>

<h3 style="font-size: 20px;"><b>📘 README.md</b></h3>
Provides:
- Overview of the project  
- How to use the repository  
- Repository structure  
- High-level workflow diagram

<h3 style="font-size: 20px;"><b>🧰 Enumeration commands</b></h3>
Contains PowerShell commands for:
- Process enumeration  
- Network enumeration  
- Registry auto-start inspection  
- IOC-oriented filtering  

<h3 style="font-size: 20px;"><b>🧱 Baseline creation + differential analysis</b></h3>
Contains:
- Baseline creation commands  
- Explanation of baseline output  
- Differential analysis workflow  
- Comparison examples
