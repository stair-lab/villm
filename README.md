# ViLLM: End2End Framework for Finetuning - Evaluation - Deployment of Vietnamese Large Language Models

## What is ViLLM?
ViLLM is an end-to-end framework for finetuning, evaluation, and deployment of Vietnamese large language models. ViLLM is designed to be a comprehensive toolkit for researchers and practitioners to work with large language models in Vietnamese. ViLLM is built on top of Hugging Face's Transformers library and provides a set of tools for finetuning, evaluation, and deployment of large language models. ViLLM is designed to be modular and extensible, allowing users to easily add new models, datasets, and evaluation metrics.

## How to install ViLLM?
### Installing Repo
Follow these steps to install Repo. The instructions are taken from the [official documentation](https://source.android.com/setup/develop#installing-repo).

```bash
# Make sure you have a bin/ directory in your home directory and that it is included in your path:
mkdir ~/bin
PATH=~/bin:$PATH
```
    
```bash
# Download the Repo tool and ensure that it is executable:
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo
```

### Cloning ViLLM
```bash
# Create a directory for the ViLLM repository
mkdir villm
cd villm
```

```bash
# Clone the ViLLM repository
repo init -b main -u https://github.com/koyejo-lab/villm.git
repo sync -j{number_of_threads}
```

### Installing Dependencies
```bash
# Install the required packages
pip install -r requirements.txt
```

## How to use ViLLM?
Instructions on how to use ViLLM for each task will be provided in the respective directories.

## How to contribute to ViLLM?
We welcome contributions to ViLLM. Please follow the instructions below to contribute to ViLLM.
- Fork the repository
- Create a new branch
- Make your changes
- Push your changes to your fork
- Contact us to discuss your changes
- Create a pull request
- We will review your pull request and merge it if it is approved
- Thank you for your contribution!

## Citation
If you use ViLLM in your research, please cite the following paper:

```
@misc{truong2024crossing,
    title={Crossing Linguistic Horizons: Finetuning and Comprehensive Evaluation of Vietnamese Large Language Models}, 
    author={Sang T. Truong and Duc Q. Nguyen and Toan Nguyen and Dong D. Le and Nhi N. Truong and Tho Quan and Sanmi Koyejo},
    year={2024},
    eprint={2403.02715},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```

## License
ViLLM is licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for the full license text.

## Contact
For any questions, please contact Sang Truong (sttruong@stanford.edu) or Duc Nguyen (nqduc@hcmut.edu.vn).

