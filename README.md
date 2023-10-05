# AI-Programming-with-python
The project is called "Use a Pre-trained Image Classifier to Identify Dog Breeds". In this project, I built a command-line application that uses a pre-trained deep learning model to classify images of dogs into different breeds. The application also determines if the image contains a dog or not.

Here's a breakdown of the project and what I learned:

Timing Code: I learned how to use the time functions in Python to measure the execution time of different parts of your code. This helps me understand the performance of your program and identify any bottlenecks.

Command Line Arguments: I implemented command line arguments using the argparse module. This allows users to pass arguments to your program when running it from the command line. In this project, I added three command line arguments: --dir for specifying the directory of the images, --arch for selecting the pre-trained model architecture, and --dogfile for specifying the file containing the list of dog breed names.

Pet Image Labels: I created a function that extracts the labels (breed names) from the image file names. I also handled hidden files by ignoring files that start with a dot (".").

Classifying Images: I used a pre-trained deep learning model (such as VGG, AlexNet, or ResNet) to classify the images. I made function calls to the model and processed the output to get the predicted breed labels. I also converted the labels to lowercase and removed any leading or trailing whitespaces.

Classifying Labels as Dogs: I compared the predicted labels with the ground truth labels (extracted from the image file names) to determine if the labels correspond to dogs or not. I assigned a value of 1 for correct dog labels and 0 for falsely classified labels.

Results: I calculated various metrics to evaluate the performance of the model, such as the percentage of correctly classified images, the percentage of correctly classified dog images, the percentage of correctly classified dog breeds, and the percentage of correctly classified non-dog images. I also displayed the results in a formatted manner which was specified in the Nanodegree Instructions.

