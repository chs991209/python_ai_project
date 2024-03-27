# <p >Jbnu AM:PM AI Project</p>   

<p></p>

## Participants:
### 문기훈, 세은, 신승호, 심은진, 최사무엘, 최현수

## Dev Stack

### <p align="center"><b>Dev Tech</b></p>


<div align="center">  
    <img src="https://img.shields.io/badge/Tensorflow-f88b00?style=for-the-badge&logo=Tensorflow&logoColor=white" alt="Tensorflow">
  <img src="https://img.shields.io/badge/Anaconda-42b049?style=for-the-badge&logo=Anaconda&logoColor=white" alt="Anaconda">
  <img src="https://img.shields.io/badge/Python-3671a1?style=for-the-badge&logo=Python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-f37726?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter Notebook">
</div>
<p></p>

###

<div align="center">
<img src="https://www.python.org/static/img/python-logo@2x.png" style="width: 350px; display: block; margin: 0 auto" alt="Python">
</div>

### <p align="center" link href=""><b>Python ver 3.8.8</b> &nbsp; 👉 [Doc for Ver 3.8.8](https://www.python.org/downloads/release/python-388/)</p>
### 

<div align="center">
<img src="https://images.velog.io/images/prayme/post/720d6efc-8dec-4d8f-8a84-b04ef10ea1a1/pngegg.png" style="width: 350px; display: block; margin: 0 auto">
</div>

### <p align="center"><b>Anaconda 3</b>&nbsp; 👉 [Release Note on 2105](https://docs.anaconda.com/free/anaconda/release-notes/#anaconda-2021-05-may-13-2021)</b></p>


0. <p>conda <span style="color: #42b049;">virtualenv를 생성</span>해 주세요</p>

        $ conda create -n env_name python=3.8.8
1. conda virtualenv list 확인

        $ conda env list
          env_name    env_directory
          other envs..

2. <p>conda <span style="color: #42b049">virtualenv 활성화</span></p>

        $ conda activate env_name
        -> (env_name)$

<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/TensorFlow_logo.svg/1200px-TensorFlow_logo.svg.png" style="width: 350px; display: block; margin: 0 auto">
</div>
<p></p>

### <p align="center"><b>Tensorflow 2.5.0</b>&nbsp; 👉 [Tensorflow 2 Installation Guide](https://www.tensorflow.org/install?hl=ko)</b></p>


###

0. <p>pip로 <span style="color: #f88b00;">tensorflow 2.5.0</span> 설치</p>

        (env_name)$ pip install tensorflow==2.5.0

1. tensorflow pip pkg 버전 확인

        (env_name)$ pip freeze | grep tensorflow
        -> tensorflow==2.5.0
    

<div align="center">
<img src="https://jupyter.org/assets/share.png" style="width: 350px; display: block; margin: 0 auto">
</div>

### <p align="center"><b>Jupyter Notebook</b>&nbsp; 👉 [Jupyter Installation Guide](https://jupyter.org/install)</p>

- <p><b>Jupyter Notebook</b></p>
    <p> -> 개발용 도구이므로 자유롭게 <span style="color: #f37726;">Windows jupyter notebook</span> 또는<br>
    IDE의 <span style="color: #f37726;">jupyter extension/plugin</span>을 설치후 활성화하여 사용이 가능합니다 (Homebrew도 가능)</p>


- <p><b>가상환경에서 패키지로 사용하고자 할 때</b></p>
  - pip installation
  
        (env_name)$ pip install notebook
