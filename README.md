# Estudo Data Science 📈
 
## Introdução
Esse repositório foi criado com a intenção de registrar o estudo praticado sobre a Ciência de Dados

## Ambiente
1. Python 3.7.8 x64
2. Última vesão dos drivers NVIDIA
2. Cuda_10.1.243_426.00_win10
3. Cudnn-10.1-windows10-x64-v7.6.5.32

## Instalação
1. Baixe ou clone o repositório na pasta do ambiente
2. Instale o VirtualEnv usando o pip 
```sh 
> pip install virtualenv
```
3. Crie o ambiente virtual 
```sh
> virtualenv .
```
4. Ative o ambiente no Windows digitando no terminal 
```sh
> .\Scripts\activate
```
5. Instale os pacotes necessários `pip install <pacote>` ou utilize `pip install -r requirements.txt`
6. Execute o Jupyter Notebook `jupyter notebook`

## Comandos
```sh
> nvidia-smi
> nvcc --version
```
```python
import tensorflow as tf
tf.config.list_physical_devices('GPU')
```
GPU
|Versão	|Versão do Python	|Compilador|	Ferramentas de criação|	cuDNN	|CUDA|
| :--- |:--- |:--- |:--- |:--- |:--- |
|tensorflow_gpu-2.3.0	|3.5-3.8	|MSVC 2019	|Bazel 3.1.0	|7.4	|10.1|
|tensorflow_gpu-2.2.0	|3.5-3.8	|MSVC 2019	|Bazel 2.0.0	|7.4	|10.1|
|tensorflow_gpu-2.1.0	|3.5-3.7	|MSVC 2019	|Bazel 0.27.1-0.29.1	|7.4	|10.1|
|tensorflow_gpu-2.0.0	|3.5-3.7	|MSVC 2017	|Bazel 0.26.1	|7.4	|10|
|tensorflow_gpu-1.15.0	|3.5-3.7	|MSVC 2017	|Bazel 0.26.1	|7.4	|10|
|tensorflow_gpu-1.14.0	|3.5-3.7	|MSVC 2017	|Bazel 0.24.1-0.25.2	|7.4	|10|
|tensorflow_gpu-1.13.0	|3.5-3.7	|Atualização 3 do MSVC 2015|	Bazel 0.19.0-0.21.0	|7.4	|10|

https://www.tensorflow.org/install/source_windows?hl=pt-br#gpu

front-end jupyterdebugger
jupyter labextension install @jupyterlab/debugger

back-end
pip install xeus-python


