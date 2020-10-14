# cnh-yoloV5

YoloV5 treinada para extrair informações de carteiras de habilitação brasileiras.  

Arquitetura: https://github.com/ultralytics/yolov5  

Link para download do modelo: https://drive.google.com/file/d/123VPUDDz2y__YEyIFZJFysUzR--gYB0e/view?usp=sharing

Uso:

python3 detect.py --weights 'cnh_yolo_weights.pt' --img 800 --conf 0.6 --source 'path/to/your/images/'

Exemplo de Output:

![alt text](https://github.com/miguelcecci/cnh-yoloV5/blob/master/readme_images/predicted_example.png?raw=true)

