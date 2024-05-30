# 가상환경 및 패키지 설치 가이드

## Tensorflow 및 Python 버전 설정 가상 환경 생성

- conda create -n tensorflow_env python=3.9
- conda activate tensorflow_env 
- pip install tensorflow

## Jupyter Notebook 설치

- pip install notebook


# Deprecated Tensorflow Keras static field parameter

## I.  lr 
<p><b>Not updated Code</b> > model.compile(optimizer=tf.keras.optimizers.Adam(lr=0.07), loss='mse')
</p>
<p> WARNING:absl:`lr` is deprecated in Keras optimizer, please use `learning_rate` or use the legacy optimizer, e.g.,tf.keras.optimizers.legacy.Adam.
</p>
<p><b>Fixed</b> > model.compile(optimizer=tf.keras.optimizers.Adam(learning_rate=0.07), loss='mse')
</p>

### lr은 deprecated 됐습니다. learning_rate을 사용해 주십시오.
- 과거 문서들에는 <b>lr parameter</b>를 쓴 문서들도 있습니다.