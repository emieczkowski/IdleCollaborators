# People Evaluate Idle Collaborators Based on the Efficiency of Distributed Systems

- **Preprint**: https://osf.io/preprints/psyarxiv/2t9w5?view_only=

### Abstract
Humans collaborate to improve productivity, but when is it acceptable for a collaborator to remain idle? Theories from distributed computer systems suggest that, depending on the task structure, division of labor leads to diminishing returns in efficiency as group size increases. We examine whether people are aware of these limitations to collaboration, and how considerations of task efficiency may affect the perceived acceptability of idleness, the withholding of effort during collaborative tasks. Across two experiments ($N = 557$), participants saw scenarios where a single dinner party guest remained idle at the table while the other guests washed dishes or prepared a salad. We manipulated task structure by varying the number of guests (group size), the amount of work to be done (workload), and the number of tools available to do it (environmental bottlenecks), which each constrain how much faster the group could have finished the task if the idle agent had contributed. Participants judged idleness as more acceptable when the idle agent's contributions would have a smaller effect on task efficiency. These judgments were best captured by a variant of Amdahl's Law, a theory from distributed systems that predicts the idle agent's potential impact by integrating group size, workload, and bottlenecks, compared to simpler heuristic models that consider a subset of these factors. Together, our findings lay the groundwork to study human collaborations as natural distributed systems. 

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
