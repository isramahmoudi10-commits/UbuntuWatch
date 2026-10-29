# 🐧 UbuntuWatch
### Linux System Monitoring and Automation Toolkit

UbuntuWatch is a practical Linux project designed to monitor system resources, display useful system information, generate reports, and automate routine monitoring tasks.

Developed on **Ubuntu Linux**, this project aims to build practical skills in Linux system administration, Bash scripting, process management, task scheduling, and version control.

UbuntuWatch is being developed step by step as a learning project, with the goal of becoming a useful command-line toolkit and a portfolio project demonstrating practical Linux skills.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Planned Features](#-planned-features)
- [Technologies](#-technologies)
- [Project Architecture](#-project-architecture)
- [Installation](#-installation)
- [Usage](#-usage)
- [Development Roadmap](#-development-roadmap)
- [Learning Outcomes](#-learning-outcomes)
- [Future Improvements](#-future-improvements)
- [Project Status](#-project-status)
- [Author](#-author)

---

## 🎯 Project Overview

System monitoring is an important part of Linux administration. Understanding CPU usage, memory consumption, available disk space, running processes, and system uptime helps users identify resource problems and better understand how a computer operates.

UbuntuWatch aims to bring these useful checks together in a simple command-line toolkit.

The project will start with basic Bash scripts and gradually introduce more advanced features, including automated reports, scheduled tasks, error handling, and optional Python-based analysis.

### Why UbuntuWatch?

- To gain hands-on experience with Linux.
- To learn how to automate tasks using Bash.
- To understand system resources and processes.
- To practice writing maintainable scripts.
- To learn professional development practices using Git and GitHub.

---

## 🎯 Objectives

The main objectives of UbuntuWatch are to:

1. Display essential Linux system information.
2. Monitor CPU, RAM, and disk usage.
3. Retrieve information about running processes and system uptime.
4. Detect resource usage that exceeds configurable thresholds.
5. Save monitoring results to log files and reports.
6. Automate repetitive checks using scheduled tasks.
7. Track development progress with Git and GitHub.
8. Explore Python for analyzing monitoring data and creating visualizations.

---

## ✨ Planned Features

The following features are planned for the project. They will be implemented and documented progressively.

### 1. System Information

Display useful information about the Ubuntu machine, such as:

- Linux kernel and operating system information.
- System hostname.
- System uptime.
- Processor information.
- Current date and time.

### 2. Resource Monitoring

Collect information about important system resources:

| Resource | Planned information |
|---|---|
| CPU | Processor information and CPU usage |
| Memory (RAM) | Total, used, available, and percentage used |
| Disk | Total, used, and available storage space |
| Processes | Running processes and resource consumption |
| Uptime | How long the system has been running |

### 3. Resource Alerts

Introduce configurable thresholds to help identify high resource usage.

Examples include:

- Warning when memory usage exceeds a defined percentage.
- Warning when disk space becomes limited.
- Reporting unusually high CPU usage.

Thresholds will be configurable as the feature is developed.

### 4. Logging

Save selected monitoring results in log files.

Planned capabilities include:

- Recording the date and time of each check.
- Saving resource usage measurements.
- Recording warnings and script errors.
- Maintaining historical monitoring information.

### 5. Report Generation

Generate simple text or structured reports containing system information and resource measurements.

Possible formats include:

- Plain text (`.txt`)
- CSV (`.csv`)
- JSON (`.json`)

### 6. Task Automation

Use Linux scheduling tools to run monitoring scripts automatically.

Possible tasks include:

- Periodic resource checks.
- Scheduled report generation.
- Automated log updates.

### 7. Python Integration

As an extension, Python may be introduced to:

- Read CSV or JSON monitoring data.
- Calculate basic statistics.
- Analyze historical resource usage.
- Generate graphs showing resource trends.

---

## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| Ubuntu Linux | Development and testing environment |
| Bash | System monitoring and automation scripts |
| Linux command-line tools | Collecting system information |
| Git | Tracking code changes |
| GitHub | Hosting the source code and documenting progress |
| Cron | Planned scheduling of recurring tasks |
| Python | Planned data analysis and visualization |

---

## 📁 Project Architecture

The project will use the following directory structure as development progresses:

```text
UbuntuWatch/
├── README.md
├── scripts/
│   ├── system_info.sh
│   ├── monitor_resources.sh
│   └── generate_report.sh
├── logs/
├── reports/
├── docs/
└── .gitignore
```

### Directory description

- **`README.md`** — Project overview, installation instructions, and documentation.
- **`scripts/`** — Bash scripts for collecting system information and monitoring resources.
- **`logs/`** — Log files produced by monitoring scripts.
- **`reports/`** — Generated system reports.
- **`docs/`** — Additional documentation, examples, and project notes.
- **`.gitignore`** — Specifies files that Git should not track.

This structure is a planned organization. Directories and scripts will be added when they are needed.

---

## 🚀 Installation

### Prerequisites

- An Ubuntu Linux environment or compatible Linux distribution.
- Access to a terminal.
- Git installed on the system.

### 1. Clone the repository

```bash
git clone https://github.com/isramahmoudi10-commits/UbuntuWatch.git
```

### 2. Enter the project directory

```bash
cd UbuntuWatch
```

### 3. Inspect the repository

```bash
ls -la
```

### 4. Run a script

Once the monitoring scripts have been implemented, their individual usage instructions will be added here.

For example, a future script may be executed with:

```bash
bash scripts/system_info.sh
```

**Note:** This example will work only after `system_info.sh` has been created.

---

## 💻 Usage

UbuntuWatch is intended to be operated from the Linux terminal.

The intended workflow is:

1. Open a terminal in the project directory.
2. Run the desired monitoring script.
3. Review the collected system information.
4. Check any warnings produced by the script.
5. Consult saved logs or reports, when those features are available.

Detailed usage examples will be added as each feature becomes functional.

---

## 🗺️ Development Roadmap

The project will be developed in stages to build a solid understanding of Linux before introducing more advanced functionality.

- [ ] **Phase 1 — Project setup:** Prepare Ubuntu, Git, GitHub, and the project directory.
- [ ] **Phase 2 — Linux fundamentals:** Practice file management, permissions, processes, and system commands.
- [ ] **Phase 3 — Bash fundamentals:** Learn variables, conditions, loops, functions, and command-line arguments.
- [ ] **Phase 4 — System information:** Create a script that displays basic machine information.
- [ ] **Phase 5 — Resource monitoring:** Collect CPU, RAM, disk, and process information.
- [ ] **Phase 6 — Logging and alerts:** Record measurements and detect threshold violations.
- [ ] **Phase 7 — Reports:** Generate readable reports and structured data files.
- [ ] **Phase 8 — Automation:** Schedule recurring checks and report generation.
- [ ] **Phase 9 — Testing and documentation:** Test scripts, handle errors, and document examples.
- [ ] **Phase 10 — Python extension:** Analyze historical data and generate visualizations.

Progress will be updated as each phase is completed.

---

## 📚 Learning Outcomes

Through this project, the intended learning outcomes include:

### Linux System Administration

- Navigate the Linux filesystem.
- Manage files and directories.
- Understand permissions and ownership.
- Inspect processes and system resources.
- Install and manage software packages.
- Understand basic services and scheduled tasks.

### Bash Scripting

- Use variables, conditions, loops, and functions.
- Execute and combine Linux commands.
- Process command output.
- Validate inputs and handle errors.
- Automate repetitive operations.

### Development Practices

- Organize a project into clear directories.
- Track changes with Git.
- Write meaningful commit messages.
- Maintain documentation with Markdown.
- Publish and maintain a project on GitHub.
- Test scripts and improve reliability.

---

## 🔮 Future Improvements

Potential improvements after the core toolkit is functional include:

- A configurable monitoring interval.
- Customizable resource thresholds.
- More detailed process monitoring.
- CSV or JSON export.
- Historical resource usage analysis.
- Graphs generated with Python.
- Improved error handling and automated tests.
- A simple dashboard or graphical interface.

These improvements will depend on the progress and scope of the core project.

---

## 📊 Project Status

**Status: In development 🚧**

UbuntuWatch is currently in its initial setup and learning stage. Features described as planned are not yet implemented unless explicitly documented otherwise.

The repository will evolve as new scripts are created, tested, and documented.

---

## 👩‍💻 Author

**Isra Mahmoudi**

Student — Engineering Preparatory Studies

GitHub: [@isramahmoudi10-commits](https://github.com/isramahmoudi10-commits)

---

## 📄 License

A license may be added when the project is ready for public distribution. Until then, no license is explicitly granted by this README.

---

*Built step by step with Ubuntu Linux, curiosity, and a commitment to learning.* 🐧
