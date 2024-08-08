# People Evaluate Idle Collaborators Based on the Efficiency of Distributed Systems

- **Preprint**: X

### Abstract
Humans collaborate to improve productivity, but when is it acceptable for a collaborator to remain idle? Theories from distributed computer systems suggest that, depending on task structure, we should expect diminishing returns to efficiency from division of labor as group size increases. We examine whether people are aware of these limitations to collaboration, and how considerations of task efficiency may affect the perceived acceptability of idleness, or the withholding of effort during collaborative tasks. We propose that people may judge idleness based on a variant of Amdahl's Law from distributed systems, used to model the task speed-up that would have occurred if the idle agent had contributed. We conducted experiments varying workload, group size, and environmental bottlenecks across scenarios in which all group members except for one were actively contributing to a common goal, and asked participants to judge the acceptability of that group member's behavior. We find that people are systematically influenced by task efficiency when judging idleness during collaborations. Simpler models based on social loafing evaluations, normative expectations, or workload considerations do not capture human judgments of idleness. Together, our findings lay the groundwork for interpreting human collaborations as natural distributed systems. 

### This repository contains:
- **Notebooks** to generate stimuli (StimulusCreation.ipynb), visualize models (Modeling.ipynb), and analyze raw experimental data (ExperimentAnalysis.ipynb)
- **Raw data** (CSV) from Prolific experiments
- Full **stimulus set**

### Prerequisites

Before you begin, ensure you have both Conda and pip installed on your system. You can install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) which is a minimal installer for Conda.

### Setup Instructions

**1. Clone the Repository**

Start by cloning this repository to your local machine. Use the following command:

```bash
git clone https://github.com/emieczkowski/IdleCollaborators.git
cd IdleCollaborators
```

**2. Create conda environment**

```bash
conda create -n idle_env python=3.9
```

**3. Activate the environment**

```bash
conda activate idle_env
```

**4. Install requirements**

```bash
pip install -r requirements.txt
```
