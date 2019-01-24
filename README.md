# Tensorflow iOS Object Detection
This repoditory is based on [csharpseattle's project](https://github.com/csharpseattle/tensorflowiOS). I appreciate his contribution. You need to set up environment of tensorflow on his procedure before building my project. All you have to do is just replace following two files.

**label_map.txt**  
List of your label setting. Don't forget to add 'display_name' in each label item, otherwise you cannot get the name while detecting. His original code will catch only the display_name parameter on detecting.

**frozen_inference_graph.pb**  
Your own model learned from TensorFlow.

![サンプル](./images/result.png)

