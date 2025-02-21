# 🚀Hands-on Protein Exploration: An LLM-Assisted Automated Education Lab🧬

Architecture:
![PEADL Flowchart](https://github.com/user-attachments/assets/da4bbb0b-7395-492a-ba4a-202b57aabf9c)

## ✨ Core Highlights ✨

* **🧠 LLM-Driven Intelligent Processes:** Utilize the powerful knowledge understanding and generation capabilities of large language models to break through the limitations of traditional protein design and create proteins with novel functions and properties.
* **🤖 End-to-End Protein Mining and Design:** Achieve full-process automation from user requirement input to experimental result analysis, significantly shortening the R&D cycle and unleashing researchers' creativity.
* **🔬 Multi-Agent Collaboration:** Simulate a team of human experts, with different agents working together to complete complex design, experimentation, and analysis tasks.
* **🧪 Deep Integration of Software and Hardware:** Seamlessly connect design, automated experimental platforms, and data analysis to achieve a truly automated closed loop.
* **🧑‍💻 Human-Centric Intelligent Interaction:** Communicate with the system through natural language, allowing even non-professionals to easily get started and explore the limitless possibilities of protein engineering.

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Core Features](#core-features)
- [Technical Architecture](#technical-architecture)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Contact](#contact)

## 🔬 Project Overview

PEADL aims to build a revolutionary integrated platform that leverages LLM and other advanced machine learning algorithms to achieve autonomous and intelligent protein design and engineering. We believe that by analyzing massive biological data, PEADL can generate innovative protein sequences, predict their structures and functions at unprecedented speeds, and accelerate breakthroughs in drug discovery, biopharmaceutical development, and basic research.

**Applications of PEADL:**

* **🏭 Biopharmaceutical Optimization:** Enhance the stability, activity, production efficiency of existing biopharmaceuticals and reduce production costs.
* **🌱 Synthetic Biology Research:** Explore and construct biological components and pathways with specific functions.
* **🎓 Education and Research Exploration:** Provide powerful automated tools for students and researchers to accelerate learning and experimental processes.

## 🏛️ Technical Architecture

PEADL adopts an advanced multi-agent architecture, with each agent performing specific tasks and collaborating to complete complex protein engineering tasks. Core technologies include:

* **Large Language Models (LLM):** The core engine driving protein design, strategy planning, and knowledge integration.
* **Heterogeneous Information Network:** Integrates multi-source biological knowledge to provide rich background information for LLM.
* **Multimodal Biological Characterization Models:** Integrates multidimensional information such as protein sequences, structures, and functions.
* **Automated Experimental Workflow Orchestration:** Transforms design plans into executable automated experimental protocols.
* **Active Learning and Reinforcement Learning:** Used to optimize experimental parameters and design strategies.


## 🛠️ Installation

To install and run the PEADL project, you need the following environment and dependencies:

- Python 3.8+
- `tensorflow`, `torch`, `biopython`, `transformers`
- For a detailed list of dependencies, please refer to `requirements.txt`

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/KRATSZ/PELLM-ADL.git
   cd PELLM-ADL
   ```

2. **Create and activate a virtual environment (recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure API key and related environment variables:**

   ```bash
   export PEADL_API_KEY="your_api_key"
   export PEADL_CONFIG="path/to/your/config/file.yaml"
   ```

   (Provide instructions for obtaining the API key, e.g., *Please visit [PEADL Official Website](https://your-peadl-website.com/api-key) to obtain your API key.*)

## 🚀 Usage

PEADL offers flexible usage options, operable through Python API or Command Line Interface (CLI):

### Python API

```python
from peadl import PEADLClient

client = PEADLClient(api_key="your_api_key")

# Submit a protein design task
design_task = client.design_protein(
    description="Design an enzyme that efficiently degrades plastic bottles",
    target_properties={"catalytic_activity": "high", "stability": "high"}
)

print(f"Task ID: {design_task.task_id}")

# Check task status and results
results = client.get_task_results(design_task.task_id)
print(results)
```

### Command Line Interface (CLI)

```bash
peadl design --description "Design a heat-resistant insulin analog" --output results.json
peadl experiment --design_id <design_id> --platform automated_lab_1
peadl analyze --experiment_id <experiment_id> --report report.pdf
```

(Provide more detailed CLI commands and parameter descriptions, e.g., *Use `peadl --help` to view all available commands and parameters.*)

## 🤝 Contributions

The development of PEADL is driven by community contributions! We welcome all forms of participation, including but not limited to:

- 📝 Submitting code (new features, bug fixes)
- 📚 Improving documentation
- 🐛 Reporting issues and making suggestions
- 📢 Sharing your user experience

### Contribution Guidelines

1. **Fork the repository.**
2. **Create a new branch** ( `git checkout -b feature/your-feature` ).
3. **Commit your changes** ( `git commit -am 'Add some feature'` ).
4. **Push to the branch** ( `git push origin feature/your-feature` ).
5. **Create a new Pull Request.**

### Code Standards

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) code style guide.
- Write clear comments and documentation.
- Run all unit tests before submission.

## 📜 License

This project is licensed under the MIT License. For more details, please refer to the [LICENSE](./LICENSE) file.

## 📬 Contact

If you have any questions, suggestions, or collaboration intentions, please feel free to contact us:

- Submit [Issues](https://github.com/KRATSZ/PELLM-ADL/issues)
- Email us at [gaoyuanbio@qq.com](mailto:gaoyuanbio@qq.com)
- Join our community forum (provide link if applicable)

**We look forward to collaborating with you to open a new chapter in protein engineering with PEADL!**
