<div align="center">

# Mohammad Zoraiz

**Engineer and researcher working across agentic AI, machine learning, quantum computing, and embedded systems.**

[![Website](https://img.shields.io/badge/mzoraiz.dev-1F6B66?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mzoraiz.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/mohammad-zoraiz/)
[![Email](https://img.shields.io/badge/Email-C2185B?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:mohammad.zoraiz@duke.edu)
[![GitHub](https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zoraizmohammad?tab=repositories)
[![Resume](https://img.shields.io/badge/Resume-4B5563?style=for-the-badge&logo=readdotcv&logoColor=white)](https://docs.google.com/document/d/e/2PACX-1vQGDRYTb37Y94P1KbrR3j_sr19AWCxf_34egeg_pSwgGWoj_7sUbTo5fb34RGZhyBWOjYocLM9GdEBL/pub)

![Profile views](https://komarev.com/ghpvc/?username=zoraizmohammad&label=Profile%20views&color=1F6B66&style=flat-square)

</div>

---

<h3>Currently</h3>


**Member of Technical Staff & SDE Intern** at Amazon AGI Lab & Kiro Labs *(May 2026 — August 2026)*

**B.S. Electrical & Computer Engineering (AI/ML), Physics, and Computer Science**, with Distinction — Duke University *(2023 — 2027)*

My work sits where learned systems meet things that have to actually run — agents that are measured rather than demoed, quantum circuits benchmarked on real hardware rather than simulators alone, and models that end up on an aircraft or a wearable. Personal site and writing at **[mzoraiz.dev](https://mzoraiz.dev)** *(source — [`mzoraiz-dev`](https://github.com/zoraizmohammad/mzoraiz-dev))*.


<details>
<summary><h2>Experience</h2></summary>

| Role | Org | When |
|---|---|---|
| **Member of Technical Staff & SDE Intern** | Amazon AGI Lab & Kiro Labs | May 2026 — present |
| **AI Data Engineering Intern** | Pfizer | Jan — Apr 2026 |
| **Machine Learning Engineering Intern** | Amazon Web Services | May — Aug 2025 |
| **Software Engineering Intern** | Amazon Web Services | May — Aug 2024 |
| **Embedded Software Engineering Intern** | Rockwell Automation | Jun — Aug 2023 |
| **Quantum Computing Researcher** | MIT Lincoln Laboratory | Feb — Dec 2022 |
| **Software Engineering Intern** | Rockwell Automation | Jun — Aug 2022 |

**Amazon AGI Lab & Kiro Labs** — architecting low-latency voice-to-agent workflows connecting Kiro code agents with streaming ASR/TTS infrastructure, and a real-time agent runtime for model-selectable coding that coordinates session state, streaming events, and autonomous code execution. *(under NDA)*

**Pfizer** — AI for genomics. Scalable data pipelines and ML workflows for model-driven analysis. *(under NDA)*

**AWS · Agentic AI** — built a serverless benchmark analysis platform adopted by the Kiro, Amazon Q, and AWS Agentic AI teams, automating large-scale code-synthesis evaluation and accelerating ML optimization by 40%. Orchestrated 120+ distributed service interactions across Lambda, DynamoDB, and S3, and integrated Amazon Bedrock to drive multi-armed bandit optimization. Work on cross-benchmark pattern detection, AST-based dependency mapping, and ML-driven error fingerprinting.

**AWS · Amazon Q Developer** — statistical analysis pipelines in Python, SQL and R; an LLM pipeline analyzer cutting error rates 15%; distributed LLM training optimization with SageMaker, Step Functions and Redshift for a 20% scalability gain.

**Rockwell Automation** — C++ firmware for L8Z motion controllers using RTOS scheduling and EtherCAT control loops (20% motion-accuracy gain), and automated C++ verification suites with GoogleTest and VectorCAST. Build pipelines on VMware, Docker and Jenkins cut build times 35%.

**MIT Lincoln Laboratory** — implemented the HHL algorithm in Q# and Qiskit for quantum fluid-flow and cognition simulations, engineering circuits with eigenvalue estimation, amplitude amplification and Hamiltonian simulation for 33% faster runtimes.

</details>

<details>
<summary><h2>Publications</h2></summary>


| Year | Venue | Work |
|---|---|---|
| 2026 | **IEEE Quantum Week — QCE26**, Poster Track | [Quantum Bayesian Learner with Hardware-Aware Circuit Compression](https://github.com/zoraizmohammad/qb-learner-compression) — how much entangling structure a quantum Bayesian learner can lose before it stops representing the task, validated on IBM's 156-qubit `ibm_fez` Heron device |
| 2024 | **IEEE SIEDS** — Systems and Information Engineering Design Symposium | [Psycho Acoustic Testing to Determine the Optimal Frequency for Audible Safety Alerts for Freediving](https://doi.org/10.1109/SIEDS61124.2024.10534714) — with Garmin International Inc. and the Duke Marine Lab ·  [`code`](https://github.com/zoraizmohammad/SonicSync) |

**Posters** — *A Cyber-Physical UAV Framework for Agentic Precision Pollination through Integrated Computer Vision, Mission-Level Reasoning, and Embedded Mechatronic Actuation*, Duke Pratt School of Engineering · [`poster + code`](https://github.com/zoraizmohammad/agentic-pollination-uav)

### In submission

**VOICE-EVPI** — *under submission to ICLR 2026.*

> **Execution-grounded, cost-sensitive clarification for voice-driven coding agents.**
>
> When a coding agent hears you, it has to decide what to do about the parts it did not quite catch. Treating that decision as a cost-sensitive value-of-information problem — where the cost is a measured property of the code being changed — rather than a confidence threshold.

More soon.

</details>

<details>
<summary><h2>Ventures</h2></summary>


**Provenia Bio** — a neuro-symbolic drug discovery system. In development.

**[Qadam · قدم](https://github.com/zoraizmohammad/qadam)** — *"a step forward."* An accessible biotech venture that packs a whole prosthetics clinic into one portable case. Roughly **65 million people** need a prosthetic or orthotic device and only about **1 in 10** has access to one — the barrier is rarely the limb itself, but the clinician, the lab, the power, and the supply chain around it. Qadam makes that whole apparatus portable: one ruggedized, solar-powered case carrying the fitting technology, tools, and standardized parts to custom-fit **15–20 limbs anywhere**, plus the open IP to make more. The intelligence lives in the fitting process; the limb the patient keeps is robust, low-cost, and purely mechanical — nothing to charge, brick, or break. · [live](https://qadam-blue-six.vercel.app)

</details>

## Selected work

<details>
<summary><b>Agentic AI and LLM systems</b></summary>

| Project | What it is |
|---|---|
| [**ombench**](https://github.com/zoraizmohammad/ombench) | Memory and backtesting for operational agents — a bitemporal history substrate, a knowledge-base compiler, and a deterministic replay harness that measures whether compiled memory *actually* improves an agent on real historical tasks |
| [**targetONCO**](https://github.com/zoraizmohammad/targetONCO) | End-to-end agentic precision oncology, from X-ray radiology to spatial proteomics tissue analysis, orchestrated by a single agent system |
| **CtrlSlash** | MCP-based documentation engine that auto-scrapes APIs and SDKs, powering semantic RAG search to cut AI IDE hallucinations — built on a $25k grant, with integrations for Cursor, Windsurf and Kiro *(private)* |
| [**agentic-pollination-uav**](https://github.com/zoraizmohammad/agentic-pollination-uav) | Autonomous pollination UAV — mission simulation and a real flight stack sharing one state machine, with an LLM planner, RAG mission memory, and a UCB1 bandit over detection thresholds |

</details>
<details>
<summary><b>Quantum</b></summary>

| Project | What it is |
|---|---|
| [**qb-learner-compression**](https://github.com/zoraizmohammad/qb-learner-compression) | Hardware-aware compression of a quantum Bayesian learner, benchmarked against post-transpile two-qubit gate count on real IBM hardware · *QCE26* |
| [**DuQuantum**](https://github.com/zoraizmohammad/duqauntum) | Duke quantum computing community site |

</details>
<details>
<summary><b>Health, bio, and genomics</b></summary>

| Project | What it is |
|---|---|
| [**LifeEdit-geneclassifier**](https://github.com/zoraizmohammad/LifeEdit-geneclassifier) | ML classifier built for Life Edit Therapeutics detecting edited vs unedited cells from single-cell expression data |
| [**RevealGenomics**](https://github.com/zoraizmohammad/RevealGenomics) | BRCA-gene cancer detection model, with Reveal Genomics |
| [**SonicSync**](https://github.com/zoraizmohammad/SonicSync) | Submersible psychoacoustic wearable delivering audible safety alerts to freedivers, with Garmin · *SIEDS 2024* |

</details>
<details>
<summary><b>Security, privacy, and signals</b></summary>

| Project | What it is |
|---|---|
| [**cipher-shield**](https://github.com/zoraizmohammad/cipher-shield) | Aggregate statistics on demographic data without ever decrypting a record — split-key homomorphic encryption with on-chain validation |
| [**SIDQ**](https://github.com/zoraizmohammad/SIDQ) | Spoof identification under degraded quality |

</details>
<details>
<summary><b>Embedded and hardware</b></summary>

| Project | What it is |
|---|---|
| [**fpga-hologram**](https://github.com/zoraizmohammad/fpga-hologram) | Persistence-of-vision rotating hologram on a Nexys A7-100T FPGA |
| [**atlas-loom**](https://github.com/zoraizmohammad/atlas-loom) | Open-source global exploration viewer |

</details>
<details>
<summary><h2>Awards and research</h2></summary>

**Awards**

- **Amazon Future Engineer Scholar** — 1 of 250 internationally, $40k, for excellence in engineering and computer science *(2023)*
- **Lockheed Martin STEM Scholar** — 1 of 100 nationally, $40k, for excellence in engineering and innovation *(2023)*
- **Dominion Energy Educational Equity Scholar** — 1 of 40 nationally, $40k, for national social impact *(2023)*
- **Congressional Commendation** — Congressman David Joyce, for community advancement in childhood education *(2022)*
- **TreeHacks winner** — CipherShield *(2025)*

**Research and activities**

- **Dark Matter & AI Research**, Kotwal Labs — high-energy physics, using AI and FPGA-integrated circuitry in dark matter search
- **ProductSpace@Duke** — Fellowship Director, leading technical product management education and mentoring multidisciplinary teams
- **HackDuke** — Organizer, coordinating logistics, sponsors and teams for tech-driven social impact

</details>

---

## Toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-1A1A1A?style=flat-square)
![VHDL](https://img.shields.io/badge/VHDL-4B5563?style=flat-square)
![Assembly x86 / MIPS](https://img.shields.io/badge/Assembly%20x86%20/%20MIPS-6E56CF?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)

**Machine learning and AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![OpenAI Gym](https://img.shields.io/badge/OpenAI%20Gym-0081A5?style=flat-square&logo=openaigym&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square)
![CNN / RNN](https://img.shields.io/badge/CNN%20/%20RNN-6E56CF?style=flat-square)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6B6B?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square)

**Quantum**

![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white)
![Q#](https://img.shields.io/badge/Q%23-3B78FF?style=flat-square)
![JAX](https://img.shields.io/badge/JAX-D24DFF?style=flat-square)
![IBM Quantum](https://img.shields.io/badge/IBM%20Quantum-052FAD?style=flat-square)

**AWS**

![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat-square)
![SageMaker](https://img.shields.io/badge/SageMaker-232F3E?style=flat-square)
![Step Functions](https://img.shields.io/badge/Step%20Functions-FF4F8B?style=flat-square)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square)
![QuickSight](https://img.shields.io/badge/QuickSight-232F3E?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)

**Cloud and infrastructure**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Data**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

**Embedded and hardware**

![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino / ESP32](https://img.shields.io/badge/Arduino%20/%20ESP32-00979D?style=flat-square&logo=arduino&logoColor=white)
![Pixhawk / MAVLink](https://img.shields.io/badge/Pixhawk%20/%20MAVLink-EE1C25?style=flat-square)
![Google Coral TPU](https://img.shields.io/badge/Google%20Coral%20TPU-4285F4?style=flat-square)
![FPGA · Nexys A7](https://img.shields.io/badge/FPGA%20%C2%B7%20Nexys%20A7-76B900?style=flat-square)
![RTOS](https://img.shields.io/badge/RTOS-2C3E50?style=flat-square)
![EtherCAT](https://img.shields.io/badge/EtherCAT-B31B1B?style=flat-square)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=flat-square&logo=google&logoColor=white)
![VectorCAST](https://img.shields.io/badge/VectorCAST-1F6B66?style=flat-square)
![Studio 5000](https://img.shields.io/badge/Studio%205000-CE181E?style=flat-square)

**Web and mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Preact](https://img.shields.io/badge/Preact-673AB8?style=flat-square&logo=preact&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

**Design and CAD**

![AutoCAD](https://img.shields.io/badge/AutoCAD-E51050?style=flat-square&logo=autodesk&logoColor=white)
![Autodesk Inventor](https://img.shields.io/badge/Autodesk%20Inventor-F7B500?style=flat-square&logo=autodesk&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Illustrator](https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square)

<sub><b>Spoken</b> — English, Urdu, Hindi (native) · Arabic, Spanish (professional working) · Turkish, ASL (basic)</sub>

---

<div align="center">
<sub><a href="https://mzoraiz.dev">mzoraiz.dev</a> · <a href="https://www.linkedin.com/in/mohammad-zoraiz/">LinkedIn</a> · <a href="mailto:mohammad.zoraiz@duke.edu">mohammad.zoraiz@duke.edu</a></sub>
</div>
