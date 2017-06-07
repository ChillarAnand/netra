# netra

Train & query MNIST dataset with different models using Tensorflow.


# Installation


    $ pip install netra


# Usage

Help:

    $ netra --help

Querying model:

    $ netra query -i https://i.imgur.com/GbreNv2.png
    $ netra query -i /foo/bar/foo.png

Training model:

    $ netra train --model regression
    $ netra train --model regression --epochs 1000 --batch_size 100
    $ netra train -m regression -e 1000 -b 100


# Sample output:

![netra](https://user-images.githubusercontent.com/4463796/26892117-e1a77a34-4bd4-11e7-91d2-11af0d1294f7.png)

![netra2](https://user-images.githubusercontent.com/4463796/26892600-773b27fc-4bd6-11e7-9bfd-38b60b88b8bf.png)
