# LabVLA

Vision-language-action models for scientific laboratories.

[Paper](https://arxiv.org/abs/2606.13578) · [Project](https://zjunlp.github.io/LabVLA/) · [Official repository](https://github.com/zjunlp/LabVLA) · [Models](https://huggingface.co/zjunlp/LabVLA)

## My contribution

I am the third author of the LabVLA paper. My work focused on LabGenesis and the generation and preparation of training data.

This is my personal fork of the team's repository, not a separate project or an official release channel.

## Using LabVLA

LabVLA combines a Qwen3-VL backbone with a flow-matching action expert for robot control. The repository includes data processing, training, fine-tuning, and deployment code.

For setup and usage, follow the [official README](https://github.com/zjunlp/LabVLA#readme). The [data processing guide](data_process/README.md) covers dataset checks and preparation.

LabGenesis-related work is part of my contribution to the research; this fork does not imply that all generation code or datasets have been released. Check the official repository for release status.

## Citation and license

Please cite the team's [paper](https://arxiv.org/abs/2606.13578) when using this work. The complete author list and BibTeX are in the [official citation section](https://github.com/zjunlp/LabVLA#-citation).

Code: [MIT](LICENSE). Original copyright notices are retained. The codebase builds on [LeRobot](https://github.com/huggingface/lerobot) and [Liger-Kernel](https://github.com/linkedin/Liger-Kernel).
