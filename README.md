A simple flask app to remove the background of an image with [Rembg](https://github.com/danielgatis/rembg)

Watch the [tutorial](https://youtu.be/cw34KMPSt4k) on YouTube

## Run it

```
pip install -r requirements.txt
python app.py
```

## Build the Docker Image

```
docker build . -t <name_of_the_docker_image:tag_number>
docker build . -t remove_background:1.0
```

## Run the Docker
```
docker run -d -p 5100:5100 image_name:version
```
