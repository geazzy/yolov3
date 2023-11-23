# Yolo v3

Projeto de exemplo do uso da ferramento Yolo_v3.

Baseado no código de https://medium.com/analytics-vidhya/object-detection-using-yolo-v3-and-deploying-it-on-docker-and-minikube-c1192e81ae7a

## Arquivos de configuração

**Yolo_v3 weights:** https://pjreddie.com/media/files/yolov3.weights

**Yolo_v3 cfg file:** https://github.com/pjreddie/darknet/tree/master/cfg

**Label file:** https://github.com/pjreddie/darknet/blob/master/data/coco.names

## Bibliotecas

```shell
pip install numpy argparse opencv-python Flask Pillow
```
## Uso/Exemplos

```shell
curl -X POST -F image=@test1.jpg 'http://localhost:5000/api/test' --output test.png
```

## Clone repo
```shell
brew install git-lfs
git lfs install
git lfs clone git@github.com:geazzy/yolov3.git
``` 
