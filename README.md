# connectome_analysis
This repository is created for the course from the Silies Lab.

This repository offers:
  - package installation of the [male](https://reiserlab.github.io/male-drosophila-visual-system-connectome/) and [female](https://codex.flywire.ai/?dataset=fafb) connectomes in Drosophila
  - how to access connectomes programmatically in python
    - accessing moprphology, connections, synapse numbers, and neurotransmitter type in jupyter notebook

### Requirements:
1. Installation
    - Visual Studio Code (https://code.visualstudio.com/)
    - Anaconda/Miniconda (https://www.anaconda.com/download)
    - Download this repository to your local pc
2. Create environment
  ### Windows
    In your anaconda/miniconda terminal run one-by-one the following lines
  ```
  cd <path-to-repository>
  conda create -n connectomics python=3.11
  conda activate connectomics
  pip install -r requirements.txt
  conda activate connectomics
  python -m ipykernel install --user --name i --display-name "connectomics"
  ```
  ### Linux/macos
  ```
  ```
3. Get your token  for the male optic lobe [here](https://connectome-neuprint.github.io/neuprint-python/docs/quickstart.html#client-and-authorization-token)
