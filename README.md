# Dockerize a nodejs application
How could we containerize a nodejs application with docker.....Let's See....

Refer this video for a hands on guide: [https://www.youtube.com/watch?v=pqsC1AcuQkU](https://www.youtube.com/watch?v=pqsC1AcuQkU)


> First clone the project
Then run : 
```sh
npm install
```

then you can build the image with : 
```sh
docker build -t image-name .
```

Its time to run the container! run:
```sh
docker run -it -p 5000:3000
```

Now head over to [http://localhost:5000](https://localhost:5000) to see the magic happen!

AWESOME!
