# tensorflow-examples

#### tensorflow build

    bazel build -c opt --copt=-mavx --copt=-mavx2 --copt=-mfma --copt=-msse4.2 //tensorflow/tools/pip_package:build_pip_package

#### using google colab <https://colab.research.google.com/notebooks/gpu.ipynb#scrollTo=t9ALbbpmY9rm>
    
    !pip install python_speech_features
    !git clone https://github.com/kevinan1/tensorflow-examples.git
    %cd ./tensorflow-examples/speech
    !python ./run.py

#### 感谢

- <https://www.zybuluo.com/hanbingtao/note/433855>
- <https://www.cnblogs.com/wsine/p/4635518.html>
- <https://github.com/xxbb1234021/speech_recognition>
- <https://github.com/katsugeneration/tensor-fsmn>
