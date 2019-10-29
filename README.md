# open-source-ideas

Do you have an open source idea that could improve science, healthcare, or is Bioinformatics-related? Then, you've found the right GitHub repository!

## Purpose

With so many of us in STEM working on grants and research, it's hard to find time to create useful tools (that aren't directly related to a project) or rewrite useful tools that can help a number of scientists by making their work easier. If you have an idea that fits that mold (even if you aren't a scientist), then please share it with us.

## Submit An Idea

View the [idea template](https://github.com/datasnakes/open-source-ideas/blob/master/idea_template.md) and add your idea to the main [README.md](https://github.com/datasnakes/open-source-ideas/blob/master/README.md) by submitting a PR.


# Project 1

Low Quality Video Enhancer

## Project Description

This is a machine learning application that can enhance video quality. A use case of the final product would be able to convert from 240p or 360p video formats to 720p or above.

## Background Information

The basic idea behind this project is to create a ML model that takes in video content of any resolution and outputs a higher quality version. To create our training set, we would downscale high quality videos to a low quality version and then provide the low quality video as input and the high quality version as the expected output. 

Some potential applications for this technology could be faster video content delivery. We could downscale videos before sending it off and then use this model to reconvert the low quality video back to high quality locally on the users device. 

### Potential Pitfalls

The first pitfall/challenge would be to decide on what algorithm to use to train the model. Another pitfall is training and prediction efficiency. Videos contain lots of data and it would require a great amount of time and resources to accurately train a finished model. The biggest challenge would be to optimize training to use up the least amount of time and machine resources as possible.

### Relevant Technology

Relevant Technology includes artificial intelligence, machine learning, deep learning, video and photo editors, databases, optimization, statistics, etc. Some common machine learning libraries are Tensorflow and Pytorch.
