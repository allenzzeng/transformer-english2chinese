# Transformer English to Chinese Translation

This repository contains code for a Transformer model that translates text from English to Chinese. Follow the instructions below to set up and run the model.

## Setup

### Clone the Repository

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/allenzzeng/transformer-english2chinese.git
```

### Create and Activate a Conda Environment

Create a Conda environment named `trans` and activate it:

```bash
conda remove --name trans --all
```

```bash
conda create -n trans python=3.8
```

```bash
conda activate trans
```

Navigate to the project directory:

```bash
cd transformer-english2chinese
```

### Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

## Configuration

By default, the model runs using CPU. If you wish to use a GPU:

1. Ensure you have a compatible NVIDIA GPU and CUDA installed.
2. Change the DEVICE setting in the code from `DEVICE = 'cpu'` to `DEVICE = 'cuda'`.

This setting is typically found on line 33 of the `transformer_nmt.py` file.

## Running the Model

To start the translation process, run the following command:

```bash
python transformer_nmt.py
```

## Additional Information

This project is learned from the work available at: [transformer-english2chinese GitHub](https://github.com/seanzhang-zhichen/-transformer-english2chinese-) [csdn](https://blog.csdn.net/qq_44193969/article/details/116016404) [embedding](https://blog.csdn.net/m0_37192554/article/details/136157084) [positional encoding](https://mp.weixin.qq.com/s/ENpXBYQ4hfdTLSXBIoF00Q).  

