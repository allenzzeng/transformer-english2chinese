# Transformer English to Chinese Translation

This repository contains code for a Transformer model that translates text from English to Chinese. Follow the instructions below to set up and run the model.

## Setup

### Clone the Repository

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/xin1347764176/transformer-english2chinese.git
```

### Create and Activate a Conda Environment

Create a Conda environment named `trans` and activate it:

```bash
conda create -n trans python=3.9
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

This project is based on the work available at: [transformer-english2chinese GitHub](https://github.com/seanzhang-zhichen/-transformer-english2chinese-).
