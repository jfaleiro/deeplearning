Deeplearning
============

*deep learning in a box*, an image carrying all the basic tools  of deeplearning

[License](LICENSE)

One image host complete with anaconda, tensorflow, and tensorboard. To use, one command, one line:

```bash
docker run -p 8888:8888 -p 6006:6006 -v .:/work jfaleiro/deeplearning:latest
```

Rinse, repeat.

You can access your jupyter instance on your port 8888:

![jupyter](images/graph.png)

And your tensorboard on port 6666:

