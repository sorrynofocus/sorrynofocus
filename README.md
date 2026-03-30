## sorrynofocus

- ai enthusiast - _i particularly enjoy STT/TTS, dynamic prosody, and semantic search_
- weathered
- ex-Broadcom/Symantec - _I spent nearly 20 years at Symantec/Broadcom. Learned alot, made awesome friends._
- [Invisible War] - _a siFi dystopian adventure/action novel I authored a long time ago (my 1st)._
- System over Syntax. _my new phrase describing "it's no longer about code anymore... it's all about system domain design"._

<!-- Insert this into readme at github root -->

<BR>

<BR>

<details>
<summary><b>Full Resume</b> (click to expand)</summary>

# Chris Winters
 
[LinkedIn](https://linkedin.com/in/christopherwinters)  |  [GitHub](https://github.com/sorrynofocus)  |  [HuggingFace](https://huggingface.co/sorrynofocus)

---

<details  open>
<summary><b>Profile</b></summary>

<BR>
Software engineer with 15+ years of experience building internal systems that improve deployment efficiency, developer productivity, and CI/CD reliability in enterprise environments.

Focused on automation, tooling, and system design, with growing hands-on experience integrating AI capabilities into real-world workflows.

---
</details>

<details  open>
<summary><b>Experience</b></summary>

### Thryv Corp - Phoenix, AZ  
**Release Manager / Deployment Systems Engineer**  
*Nov 2024 – Present*

- Reduced deployment time from 2 hours to 45 minutes (**45% improvement**) by eliminating manual Jira operations through a Python CLI tool (`jiraop`) that automated bulk ticket transitions (~100 tickets), validation checks, and deployment state verification  
  **Tech:** Python, Jira API, CLI tooling

- Removed manual deployment orchestration overhead by building `autoDeployHelper` to determine stage vs production artifact placement and generate clean deployment inputs (CSV), reducing human error and streamlining multi-stage release workflows  
  **Tech:** Python, GitHub, CircleCI, CSV processing

- Eliminated manual copy/paste workflows and inconsistent deployment tracking by developing a deployment extractor that gathers artifacts and GitHub tags and outputs structured data (CSV/JSON) for reliable downstream automation and reporting  
  **Tech:** Python, data parsing, JSON/CSV

- Improved deployment documentation efficiency by an additional **45%** by automating Confluence page generation using templates and a Python-based updater tool that dynamically injects Jira queries, key dates, and deployment metadata via GitHub Actions  
  **Tech:** Python, Confluence API, HTML parsing, GitHub Actions

- Established early-stage architecture and documentation standards to support future independent deployment models across teams, reducing reliance on centralized release coordination  
  **Tech:** Process design, Jira, Confluence

---

### Symantec / Broadcom - Los Angeles, CA  
**Software Development Engineer / Release Engineer**  
*2007 – Feb 2024*

- Reduced manual Jenkins maintenance effort from days to ~1 hour and eliminated repetitive credential update work by building automation jobs and scripts to manage credentials, VM updates, and system configurations across ~20 servers  
  **Tech:** Jenkins (Groovy), Python, Shell scripting, VM automation

- Improved CI/CD efficiency by **~60%** by developing a reusable Python-based Perforce SDK (CM-SDK) that replaced duplicated scripts with simplified APIs (e.g., branching/integration reduced to ~15 lines of code), enabling consistent and scalable source control operations  
  **Tech:** Python, Perforce API

- Eliminated ~2 hours of manual release overhead per build by developing `signpubs`, a C++ tool that automated Live Update Publishing and signing workflows, later adopted across multiple teams for over a decade  
  **Tech:** C++, CI/CD systems

- Reduced debugging time by up to **4 hours per incident** by building Jenkins tooling that automated system updates, improved visibility, and minimized manual intervention during pipeline failures  
  **Tech:** Jenkins, Groovy, automation scripting

- Designed and implemented CI/CD automation systems integrating testing, deployment, and infrastructure workflows, improving consistency and scalability across enterprise applications  
  **Tech:** Jenkins, Docker, Python, Groovy, GCP

### Software Engineer — pcAnywhere Team  
*2001 – 2006*

- Began as a mid-level engineer focused on debugging and support, resolving complex issues in C/C++ codebases and improving product stability across customer environments  
  **Tech:** C/C++

- Developed custom installer actions and debugging tools using C/C++, InstallShield, and MSI APIs to improve installation reliability and streamline troubleshooting workflows  
  **Tech:** C/C++, InstallShield, MSI APIs

- Transitioned into Configuration Management / Release Engineering to address fragmented and inconsistent build systems across teams, leading efforts to standardize and unify build processes  

- Built and contributed to a centralized build system (Jenkins-like architecture) supporting security isolation, build orchestration, reporting, and user management across **15+ teams and 100+ developers**, improving build reliability and reducing system fragmentation  
  **Tech:** PHP, MySQL, Java (agent communication)

- Enabled cross-platform build support for Windows, Linux, Solaris, AIX, and AS-400 systems, ensuring consistent build and deployment workflows across diverse environments  
  **Tech:** Linux, Windows, AS-400, Solaris, AIX

- Maintained and supported distributed build infrastructure across multiple operating systems, improving system stability and developer productivity  

---
</details>

<details>
<summary><b>Accomplishments</b></summary>

<BR>

- Reduced infrastructure footprint from 500 to 90 servers (**82% reduction**) by implementing dynamic VM provisioning using custom plugins and template-based provisioning in vSphere, Nutanix, and GCP, enabling on-demand resource allocation aligned to workload requirements while operating within environment security constraints  
  **Tech:** VMware vSphere, Nutanix, GCP, custom provisioning plugins

- Improved CI/CD efficiency by **~40%** by standardizing pipelines as code using Jenkins DSL, enabling consistent, maintainable, and easily updatable build and deployment workflows across projects  
  **Tech:** Jenkins DSL, Python, Docker

- Prevented CI/CD pipeline blocking during Microsoft DTM driver signing by developing a Python-based system to checkpoint (“freeze”) builds while awaiting external signing and safely resume (“unfreeze”) with signed binaries, enabling continued parallel build execution  
  **Tech:** Python, CI/CD systems, build orchestration

- Improved deployment automation reliability by **~10%** by developing “Mapotamus,” a C# WinForms application that replaced unreliable drive-mapping scripts with a centralized system for managing mapped drives, encrypted credentials, and pre-build task execution across dynamically provisioned VMs, enabling consistent Jenkins agent setup via self-updating configuration through Artifactory (pull-based updates)  
  **Tech:** C#, WinForms, Artifactory, VMware ESX, Nutanix, GCP

---
</details>

<details>
<summary><b>Technical Skills</b></summary>

<BR>

**Languages:** Python, C#, C++, Groovy (working knowledge), Shell/Bash (WSL)  

**Systems Programming:** Win32 API (native Windows development)  

**CI/CD & DevOps:** Jenkins (Pipeline/DSL), Artifactory (working knowledge), Perforce (working knowledge), GitHub, Docker, GitHub Actions (working knowledge), CircleCI (working knowledge)  

**Cloud & Infrastructure:** Azure (hands-on), Google Cloud Platform (GCP) (working knowledge), VMware vSphere (working knowledge), IaC  

**Tools:** Jira, Confluence, Visual Studio, VSCode  
**Testing:** Coverity, Bullseye, Beyond Compare  

**AI (Hands-on):** Azure Cognitive Services, Azure OpenAI / Foundry, Copilot, Codex, Hugging Face (working knowledge)

---
</details>

<details>
<summary><b>Certification</b></summary>

<BR>

- Microsoft Certified: Azure AI Fundamentals (AI-900)  
- Google Cloud Infrastructure Certifications  
- Linux Foundation: Developing Secure Software  

---
</details>

<details>
<summary><b>Projects</b></summary>

<BR>

- **STT AI Assistant**  
  *Problem:* Needed a way to interact with tools and workflows using natural speech  
  *Solution:* Built a speech-to-text → processing → text-to-speech pipeline integrating Azure AI services; solved real-time orchestration challenges (threading, latency, service lifecycle)

- **VisionOCR**  
  *Problem:* Extracting text from screenshots/images was unreliable and manual  
  *Solution:* Built a C# desktop tool using Azure AI Vision to quickly and accurately extract text from images

- **Jotter (Active Development)**  
  *Problem:* Wanted a lightweight, cloud-free way to store and retrieve useful information across environments  
  *Solution:* Developing a WPF-based desktop tool with structured local storage and multi-window note management while learning modern UI patterns
</details>

</details>  


[Invisible War]: https://www.amazon.com/Invisible-War-Chris-Winters/dp/0998020915/ref=sr_1_1?dchild=1&keywords=chris+winters+invisible+war
