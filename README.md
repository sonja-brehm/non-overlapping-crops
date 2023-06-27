# Non-overlapping image crops

A simple code to crop all images in a directory into multiple patches. 

-> Cuts the images into non-overlapping square patches with a minimum width of 1024, as illustrated in this example:

<img src="img_example.png" width="700"/>

I specifically wanted crops that don't overlap, as opposed to the multicrop.py script from [dataset-tools](https://github.com/dvschultz/dataset-tools), which produces randomised multi-scale crops. I was interested in how the results would differ when using the resulting datasets to train a generative model.

The code is currently stored in a jupyter notebook, but I will soon add a python script that can be run from the terminal.
