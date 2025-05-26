# connectome_analysis
This repository is created to investigate the Tm9/Tm1 upstream connectivity in _Drosophila melanogaster_ for the summer course 2025 of the Silies Lab.

This repository offers:
  - package installation of the [male](https://reiserlab.github.io/male-drosophila-visual-system-connectome/) and [female](https://codex.flywire.ai/?dataset=fafb) connectomes in _Drosophila_
  - how to access connectomes programmatically in python
    - accessing moprphology, connections, synapse numbers, and neurotransmitter type in jupyter notebook

### Installation:
1. Requirements
    - Visual Studio Code (https://code.visualstudio.com/)
    - Anaconda/Miniconda (https://www.anaconda.com/download)
    - Download this repository to your local pc (https://github.com/mariaioan/connectome_analysis/tree/main)
    - For Windows: https://git-scm.com/downloads/win
    - Download 'Connections (Unfiltered) (212 MB)' from https://codex.flywire.ai/api/download?dataset=fafb in your repo folder
2. Create environment <br />
   ##### In your anaconda/miniconda terminal run one-by-one the following lines
   
    #### Windows 
      
    ```
    cd <path-to-repository>
    conda create -n connectomics python=3.11
    conda activate connectomics
    pip install -r requirements.txt
    ```
    #### Linux
    ```
    cd <path-to-repository>
    conda create -n connectomics python=3.11
    conda activate connectomics
    sudo apt install git
    pip install -r requirements.txt
    ```
    #### macos
     ```
    cd <path-to-repository>
    conda create -n connectomics python=3.11
    conda activate connectomics
    Install brew if needed: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    brew install git
    pip install -r requirements.txt
    ```
4. Get your token for the male optic lobe [here](https://connectome-neuprint.github.io/neuprint-python/docs/quickstart.html#client-and-authorization-token)
5. (Optional) Get yout token for the female connectome [here](https://fafbseg-py.readthedocs.io/en/latest/source/tutorials/flywire_setup.html)
6. Open you VS code, open the main script connectomics_analysis.ipynb, connect the kernel/enc (connectomics) on the top right, and run the cells. Probably you will need to install the Python and ipykernel addons in VS code.
