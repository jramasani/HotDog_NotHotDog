# hotdog-nothotdog
"What would you say if I told you there is a app on the market that tell you if you have a hotdog or not a hotdog?"  -Jian-Yang

This is a TensorFlow Image Classifier that can be used to classify whether an image is hotdog or nothotdog. Inspired by Mr. Jian-Yang from HBO's Silicon Valley. [Watch Demo here!](https://www.youtube.com/watch?v=ACmydtFDTGs)

Used Google CodeLabs' [TensorFlow For Poets](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0) as a guide. 

## Requirements:
  1. Docker
  
## Usage:
  1. Clone the repo and start tensorflow docker image
  ```
  docker run -it   --publish 6006:6006   --volume ${HOME}/tf_files:/tf_files   --workdir /tf_files   tensorflow/tensorflow:latest-devel
  ```
  2. Run the label_hotnot script to label the image. 
 ```
 python /tf_files/label_hotnot.py /tf_files/testImages/hotdog.jpg
 ```
 ## Tests:
 1. hotdog
![result_hotdog](https://user-images.githubusercontent.com/8012968/28502253-1506c7c6-700c-11e7-8608-710f401ec81d.png)

 2. Something else
 ![Image of rose result]
 ![result_rose](https://user-images.githubusercontent.com/8012968/28502254-153ce7b6-700c-11e7-8d0f-28b20391d451.png)
 
 
 
          

  
