# Hack the North 2019 - TrashDash

## Inspiration
Approximately one third of our planet’s food—1.3 billion tonnes—is wasted each year. Resources for food growth and transportation are wasted when food remains uneaten. The impact this has on the environment is detrimental. Enter TRASHDASH. An image recognition tool that provides insights to reduce food waste. Using computer vision, TRASHDASH determines what food is most often wasted, in order to give chefs and food service owners insight on what foods not to make. This will ultimately reduce food waste.

## How we built it
Our solution is an artificial intelligence based web application using Mask R-CNN that allows public cafeterias to track what kind and how much food is thrown away. By using image recognition, it allows the users to ensure that the amount of food wasted is decreased for future meals.

## Challenges we ran into
Our initial idea was to utilize a raspberry pi attachable camera but were unable to because it was unable in the hardware lab so instead we innovative and used google images instead. There was a learning curve for a few of the members in the group who hadn’t worked with API’s in the past but were quick to learn the information.

## Accomplishments that we're proud of
Our machine learning models did very well, and yielded very useful information. We were able to manipulate the different API’s we used fairly well and we created an aesthetically appealing web interface. Lastly we are proud to be able to present this information in a very clean and concise manner to the user through our web app.

## What we learned
We learned important problem-solving skills, and how to leverage data and create models to produce accurate solutions. We were all introduced to a new way of transferring data from one place to another through the Flask framework and many of us learnt a lot about the capabilities of machine learning. Overall, we worked well as a team and learnt a lot from one another.

## Requirements
Python 3.4, TensorFlow 1.3, Keras 2.0.8 and other common packages listed in `requirements.txt`.

## Installation
1. Install dependencies
   ```bash
   pip3 install -r requirements.txt
   ```
2. Clone this repository
3. Run setup from the repository root directory
    ```bash
    python3 setup.py install
    ``` 
3. Download pre-trained COCO weights (mask_rcnn_coco.h5) from the [releases page](https://github.com/matterport/Mask_RCNN/releases).
