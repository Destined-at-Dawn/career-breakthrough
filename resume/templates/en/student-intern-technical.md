# Resume Template: Student Intern · Technical

> Use case: Technical roles (SWE/EE/FPGA/Embedded), project-heavy layout
> Format: One page, ATS-friendly, technical depth

---

## [Your Name]

[City] · [phone] · [email] · [github.com/yourname] · [linkedin.com/in/yourname]

---

### Education

**[University Name]** — B.S. in [IC Design / Electrical Engineering]　　**[2025 – 2029]**

- GPA: **[3.9]/4.0** | Coursework: [Digital Logic, Embedded Systems, Computer Architecture, Signals & Systems]

---

### Projects

**[FPGA Digital Design — Competition Project]**　　**Team Lead**　　**[Jan – Apr 2026]**

Designed and implemented a complete data transmission pipeline on FPGA with encryption and error checking.

- **Communication Interface Module**: Hand-coded RTL (no IP cores), standard baud rate, with custom testbench covering normal, edge-case, and error scenarios — 100% functional verification pass rate
- **Data Processing Module**: Pipelined implementation, optimized critical path through critical path redesign and pre-computation optimization
- **Data Integrity Checker**: Single-cycle combinational logic, verified against standard test vectors
- **Stack**: Verilog HDL · Icarus Verilog · GTKWave · Yosys · nextpnr

**[ROS Autonomous Navigation — Robotics Competition]**　　**Integration Lead**　　**[Feb – Mar 2026]**

Built a complete navigation pipeline for a wheeled robot with dynamic obstacle avoidance.

- Configured **move_base** framework from scratch: global/local costmaps, TF coordinate transforms, planner parameters
- Tuned **base_local_planner** parameters (controller_frequency, PID gains) for smooth path tracking in dynamic environments
- Debugged 3 parameter mismatches between code and competition rules using systematic file-by-file comparison
- **Stack**: ROS Noetic · Gazebo 11 · Python · move_base

---

### Skills

| Category | Technologies |
|----------|-------------|
| HDL/EDA | Verilog, Icarus Verilog, GTKWave, Vivado, Yosys, nextpnr |
| Embedded | C, STM32 (basic), Linux, Git |
| Robotics | ROS Noetic, Gazebo, move_base, TF, PID control |
| AI Tools | Claude Code, Gemini Pro, NotebookLM |

---

### Awards

- [1st Place, University Speech Competition (2026)]
- [National Computer Exam Level 2 — C Language (2026)]

---

<!-- Technical version key differences from Minimal:
1. Projects section is DETAILED — module-level granularity with specific parameters
2. Each project bullet includes quantified metrics (timing optimized, 100% pass rate)
3. Tech stack listed per project, not just in a skills section
4. GitHub link in header — let the code speak
-->
