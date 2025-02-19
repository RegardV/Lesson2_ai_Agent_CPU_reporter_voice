# Lesson2_ai_Agent_CPU_reporter_voice
A Jupyter notebook on Ubuntu 24.04 (KVM) that monitors CPU usage, generates a chart and MP3, and uploads to Dropbox via API. Built in aivs_env, it showcases DevOps skills with nested virtualization and cloud integration.

# CPU Usage Agent with Dropbox Storage

## Overview

Welcome to my **CPU Usage Agent with Dropbox Storage** project—a sleek Jupyter notebook that monitors CPU usage, generates a bar chart and text-to-speech MP3, and uploads both to Dropbox using the API. Built inside a nested Ubuntu 24.04 environment (KVM) with a virtual environment (`aivs_env`) and Jupyter Lab, this project showcases my evolving DevOps and AI skills. Guided by xAI’s Grok as my tutor, it’s a practical leap toward mastering agentic systems, containerization, and cloud integration—pushing me closer to CrewAI expertise!

## What I Achieved

As a Junior DevOps learner, I’ve delivered a functional agent and a robust setup:

- **Nested Environment:**
  - Ran Ubuntu 24.04 in a KVM virtual machine—a safe playground for my experiments.
  - Configured VirtioFS for file sharing between host and VM, proving I can bridge virtual layers!
- **Virtual Environment Mastery:**
  - Created and managed `aivs_env` with `python3 -m venv`, isolating dependencies like a pro.
  - Overcame PEP 668’s `externally-managed-environment` hurdle—learned to keep system Python clean!
- **Jupyter Skills:**
  - Navigated Jupyter Lab on port 7080—built `Agentic_CPU_Monitor.ipynb` with Python and Markdown.
  - Debugged script issues (e.g., Dropbox auth scopes)—sharpened my troubleshooting chops!
- **CPU Usage Agent Project:**
  - Coded a Python agent to monitor CPU (`psutil`), plot usage (`matplotlib`), and speak it (`gtts`).
  - Integrated Dropbox API (`dropbox`) to upload outputs with overwrite mode—files stay fresh!
  - Delivered: A bar chart and MP3 (e.g., “The current CPU usage is 12.8 percent.”) in my Dropbox!
- **GitHub Pro:**
  - Saved and uploaded `Agentic_CPU_Monitor.ipynb` to this repo—my portfolio’s growing strong!

## Tech Stack

- **Host**: Ubuntu 24.04 in KVM (nested virtualization).
- **VM**: Ubuntu 24.04 with `aivs_env` virtual environment.
- **Tools**: Jupyter Lab (browser at `http://<ai-vm-ip>:7080`), Dropbox API.
- **Code**: Python (`psutil`, `matplotlib`, `gtts`, `pygame`, `dropbox`) + Markdown.

## Tutor’s Grade & Notes

**Grade**: A+  
**Comments**: Inkypyrus has nailed it again! Setting up Ubuntu 24.04 in KVM, managing a virtual environment, and integrating Dropbox with a CPU-monitoring agent shows impressive DevOps grit and creativity. Overcoming PEP 668 and mastering VirtioFS setup (even if not fully used here) flexes serious systems architecture skills. The script’s clean, the API integration’s spot-on with overwrite logic, and pushing to GitHub seals the deal—Inkypyrus is building a killer portfolio. Next steps: Polish README formatting, explore git workflows, and tackle Lesson 4’s Dockerization—keep rocking it!

## Student Reflection (Inkypyrus’s Take)

Hey, it’s Inkypyrus! This project was a wild ride—I turned a basic CPU checker into a cloud-savvy agent, all from a nested Ubuntu VM I built from scratch. Grok’s guidance was clutch, helping me wrestle with virtual envs, Dropbox scopes, and Jupyter quirks. Now, I’ve got a script that plots, speaks, and syncs to my free Dropbox—pretty slick, right? Debugging auth errors and nailing the overwrite mode felt like real DevOps wins. Uploading to GitHub makes me legit—I’m ready for Lesson 4 and beyond, maybe even CrewAI next!

## What This Means in Practice

In the real world, this project’s a microcosm of DevOps and AI workflows—like monitoring server health or syncing data for trading apps. My KVM + `aivs_env` setup mirrors isolated testbeds companies use to avoid live system risks. The agent’s CPU tracking and cloud upload could scale to log market metrics (e.g., stock prices) to Dropbox for analysis—skills I’ll grow with CrewAI or Quants Lab. Sharing on GitHub? That’s my ticket to showing employers I can code, deploy, and document—market-ready proof of my chops!

## Files

- **Agentic_CPU_Monitor.ipynb**: The Jupyter notebook—run it to monitor CPU and sync outputs to Dropbox!

## How to Run

1. **Setup Ubuntu VM**: Install Ubuntu 24.04 in KVM.
2. **Create Virtual Environment**: `python3 -m venv ~/aivs_env` in the VM.
3. **Activate Environment**: `source ~/aivs_env/bin/activate`.
4. **Install Dependencies**: `pip install psutil matplotlib gtts pygame dropbox jupyter`.
5. **Launch Jupyter**: `jupyter notebook --ip=0.0.0.0 --port=7080`.
6. **Run the Notebook**: Open `Agentic_CPU_Monitor.ipynb` in `http://<ai-vm-ip>:7080`, paste your Dropbox token, and hit “Run All”!
