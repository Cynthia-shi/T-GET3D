## T-GET3D: A Generative Model of High Quality 3D Textured Shapes Guided by Texts<br>


- Clone the githab code
```bash
cd YOUR_CODE_PATH
git clone https://github.com/Cynthia-shi/T-GET3D.git
cd T-GET3D
```

- Build Docker image

```bash
cd docker
chmod +x make_image.sh
./make_image.sh t-get3d:v1
```

- Start an interactive docker container
  
```bash
docker run -dit --network POETIC-FLOWER-Network --shm-size 256G --gpus all --name t-get3d -v /home/cynthia/Projects/T-GET3D:/T-GET3D t-get3d:v1 bash
```
  






