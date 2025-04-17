# deep-learning based text classification

##  Reference
1 Paper:[Convolutional Neural Networks for Sentence Classification](https://arxiv.org/abs/1408.5882)

2 Shawn1993:(https://machinelearningmastery.com/sequence-classification-lstm-recurrent-neural-networks-python-keras/)
## Dateset
[Movies Reviews made by cornell](https://www.cs.cornell.edu/people/pabo/movie-review-data/rt-polaritydata.tar.gz)



## Report

![Text CNN](https://i-blog.csdnimg.cn/blog_migrate/e9a650dd82da0e885e8b913a85a0edfd.png#pic_center)
### Main idea
#### 1
They used a simple modification based on mature CNN model to allow for the use of both dynamic and stactic vectors by deploying two channels.
Concerned the static vectors,They matain their fixed feature,In term of the dynamicThey deploy the backpropagation to updata the vectors.

#### 2
They used different kernel_size to capture features from the word sequences of varing lengths.To some extent,They achieved commuication betweeen words in sequences.
### Difference compare to the traditional
The traditional CNN use the square-shaped convolutional kernal and keep fixed thoughout,sharing the same parameters.Due to the kernel_size,the traditional will capture features from  finer granularity.

The text CNN: The input is a embedding matrix.Every row represents a word in the form of vector.The dimension of the vector equal to the width of convolutional kernal. Thus ensuring the word serves as the mininal# deep-learning based text classification


#### Introducing the dropout to prevent overfitting.





