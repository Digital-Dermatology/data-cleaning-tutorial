![Data Cleaning Tile](images/data-cleaning-tile.png)

# Summary

Modern data cleaning approaches will be presented, explained, and critically reviewed with a focus on emerging tools for image dataset curation.
Automatic detection of data quality issues in data collections of growing size will be motivated by reviewing contamination in popular benchmarks and by assessing its impact on the training and evaluation of machine learning models.
Data cleaning will be shown to be complementary to learning with noise, although it is not quite as known.
Particular attention will be paid to near-duplicate images, which can lead to train-evaluation data leaks, irrelevant samples, which are invalid within their context, and label errors, which corrupt the learning signal.
The major repositories containing resources for data cleaning will be presented with their strengths and weaknesses, used in guided examples, and participants will be encouraged to clean their own datasets in the closing part of the tutorial.

# Agenda

- 14:00 -- 14:45 Phenomenology of data quality issues
- 14:45 -- 15:30 Modern data cleaning methods
- *15:30 -- 16:00 Coffee break*
- 16:00 -- 16:15 Modern data cleaning libraries
- 16:15 -- 17:15 Hands-on session: clean your own image dataset
- 17:15 -- 17:30 Discussion of findings and wrap-up

# Preparation

A UNIX-like command line terminal is needed, as found natively on Linux and OS X or available on Windows via e.g. WSL.

## Requirements for cleaning your own dataset

If you want to try cleaning on your own image dataset instead of a toy one, it should fulfil the following criteria:

1. Between 1'000 and 5'000 images is best, between 500 and 10'000 images is ok
1. Resolution at least 128 x 128 (images will be resized to 224 x 224)
1. Image formats `.jpg`, `.jpeg`, `.png`, `.ppm`, `.bmp`, `.pgm`, `.tif`, `.tiff`, `.webp`
1. Only a single classification label per image is supported for label errors
1. In this case, images should be in subfolders by class (e.g. `dataset/class1/image1.jpg`)

These are suggestions to achieve good results by the end of the tutorial.
Since some methods and tools have longer runtimes, we will recommend what to try first and you should also take your hardware into account.

# Speakers

| Simone Lionetti | Fabian Gröger |
|:--:|:--:|
| ![Simone](images/simone.jpeg) | ![Fabian](images/fabian.jpeg) |
| Algorithmic Business Research Lab<br>Department of Informatics<br>Lucerne University of Applied Sciences and Arts | Digital Dermatology Group<br>Department of Biomedical Engineering<br>University of Basel |

# Links

- [AMLD EPFL 2024 Website](https://2024.appliedmldays.org)
- [Tickets](https://ti.to/applied-machine-learning-days/2024)

# Format

Our workshop will consist of short theoretical explanations, critical discussions of pros and cons, presentations of tools, and guided and independent coding sessions.
Participants not only have the chance to ask for explanations, but also to bring in their own experience, contributions and opinions which will be abundant on such an ubiquitous topic.
Moreover, attendants can follow illustrative, stimulating examples and apply what they have learned to an own problem.

# Objectives

Participants will get to know the working principles of modern data cleaning strategies, the different sub-problems they address and their impact on machine learning models.
They will learn which packages are available to automate the curation of datasets, including their functionalities, the computational resources required, and their scalability.
At the end of the session, attendants will have gained a set of tools to examine and improve essentially any dataset they will encounter.

# Audience

Given that the topic of data quality is almost ubiquitous and often neglected, our audience includes any user of data-driven methods and/or anyone with the goal of collecting a good dataset.
This can range from students at the end of their bachelor to established researchers and experienced consultants, mostly in computer science but also biology, engineering, medicine, and so on.
Thanks to the mix of basic and advanced topics, most people will have something new and interesting to take home.
