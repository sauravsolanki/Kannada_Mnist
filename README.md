# Kannada_Mnist
This is submitted against the Kaggle Contest mentioned below. 


-----

# [Kannada MNIST Challenge](https://www.kaggle.com/c/Kannada-MNIST)

## Problem statement
    The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine, in the Kannada script.

    Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

    The training data set, train.csv, has 785 columns. The first column, called label, is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

    Each pixel column in the training set has a name like pixel{x}, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixel{x} is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

    For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below.

    Visually, if we omit the "pixel" prefix, the pixels make up the image like this:

    000 001 002 003 ... 026 027
    028 029 030 031 ... 054 055
    056 057 058 059 ... 082 083
     |   |   |   |  ...  |   |
    728 729 730 731 ... 754 755
    756 757 758 759 ... 782 783 
    The test data set, test.csv, is the same as the training set, except that it does not contain the label column.

    The evaluation metric for this contest is the categorization accuracy, or the proportion of test images that are correctly classified. For example, a categorization accuracy of 0.97 indicates that you have correctly classified all but 3% of the images.
## Data description
    train.csv - the training set
    test.csv - the test set
    sample_submission.csv - a sample submission file in the correct format
    Dig-MNIST.csv - an additional labeled set of characters that can be used to validate or test model results before submitting to the leaderboard

-----

## Repo
1. ./Kannada_Mnist.ipynb
