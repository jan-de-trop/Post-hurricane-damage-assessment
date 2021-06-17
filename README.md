# Post-hurricane-damage-assessment

The datadset can be found here: https://drive.google.com/file/d/1CIv7wheOC0TgQArukUDWjPd3tJqckmRp/view
g
## Motivation and About the Project

Damage assessment is one of the most important steps of disaster response, after the onset of a hurricane. For example, assessing the impact on the number of flooded buildings can help emergency managers, disaster relief organizations and responders in creating a plan of action. We propose a model that classifies satellite images of buildings into unaffected and flooded. Such automation saves the time required to manually visit the damaged sites to assess impact. Our approach was to use SOTAS on images & use an Auto-Encoder based, to see which one is more optimal

## Data and Labels

The data set comprises RGB images of resolution 128x128, representing damaged and unaffected buildings. The images are divided into four groups: (1) a training set consisting of 5000 images: (2) a validation set of 1000 images: (3) a balanced test set of 1000 images: (4) an unbalanced test set of 9000 images.

Test data of Hurricane Delta was included by processing Geospatial Images

## Conclusion and Future Work

A robust model for classifying post hurricane damaged buildings from the unaffected ones is proposed in this project. By using Learning Rate Finder & Scheduled Learning Rate, the overall test accuracy could be boosted to 98-99%. Based on the experiments, it can be observed that using an Auto-Encoder further enhances the model performance. The solution can be generalised across different hurricanes, and can thereby assist relief helpers and policymakers in decision-making

The results can be improved by training the model with larger and more diverse hurricane datasets across different geographies In addition, changes can be made to the decoder architecture to pre-process the image in different color spaces
