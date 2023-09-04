# Sociata (Vinelab) projects recap

From May to August 2019, I was an intern at Vinelab (rebranded to Sociata in 2022), in Beirut, Lebanon. I worked primarily on the research and development of Machine Learning solutions for Social Media analysis. This was done during my second year in Engineering School (4th year post High School), which required a 4-month internship during said year.\*  
Here is a quick recap of all my GitHub repositories linked to this internship, in chronological order. Keep in mind that as I was still in training, these projects may not be ideal in terms of code clarity or documentation.    

For professional reasons, I have decided to make said repositories private, though at time of writing, they are still accessible through GitFont links.    
You may access them by clicking on the following project names.  

\*: *To learn more about my work experience, feel free to consult [my LinkedIn profile](https://www.linkedin.com/in/mathieu-seraphim/).*

## [InstagramInfluencerFakeFollowerProportion](https://gitfront.io/r/MathieuSeraphim/G8L8BdyQ6UWK/InstagramInfluencerFakeFollowerProportion/)

My attempt to use a classification model to determine Instagram bots or "fake" followers.    
It is more a recap of my actions and conclusions than a real project, though.    

It is well documented.

## [ImageLabelExtractor](https://gitfront.io/r/MathieuSeraphim/CwSVwCuLfPzd/ImageLabelExtractor/)

Uses the ResNet50 image classifier, trained on the ImageNet dataset and included in Keras, to classify images and extract the five best labels (classifications for the image), with their corresponding confidence scores.    
Intended as a test projects, just to see if it works.    

Includes no documentation.

## [VideoLabelExtractor](https://gitfront.io/r/MathieuSeraphim/WRaH8WnzVwxF/VideoLabelExtractor/)

Same as above - but takes a video as argument, and divides it into multiple images (one per scene) before analysis.

## [LabelProject](https://gitfront.io/r/MathieuSeraphim/iDmP9PNTjQDy/LabelProject/)

Given an Instagram public account, scrapes any amount of images that you want and extracts their label using ResNet50, before exporting all the data gathered in a JSON file.    

A fully standalone and well documented project. I'm pretty proud of it.

## Mask_RCNN
*No link for this one, due to the limitations of free GitFront accounts at time of writing.*    
*Feel free to message me if you somehow want access.*    

Another test, this time using an image segmentation model trained on Microsoft's COCO dataset.    

Again, no documentation to speak of.

## [ObjectDetector_crude](https://gitfront.io/r/MathieuSeraphim/mr5Ghpzk3Z58/ObjectDetector-crude/)

A kind-of-messy adaptation of the TensorFlow pretrained models API. This time, the model is ResNet V2, trained with a subset of Google's Open Images dataet, for the purpose of object detection.    
Contains a lot of unnecesary documents, in many ways inferior to the next repository.    
It is however functional, and will output images with bounding boxes, which the next repository does not do.    

Somewhat documented.

## ObjectDetectorAndLabeler
*No link for this one, due to the limitations of free GitFront accounts at time of writing.*    
*Feel free to message me if you somehow want access.*    

Same as above, but more standalone, and returns only labels. Also, *cleaner*.    

Well documented.

## Antimony
*No link for this one, due to the limitations of free GitFront accounts at time of writing.*    
*Feel free to message me if you somehow want access.*    

Project for scraping and labeling images an videos.    
Modular and more or less well coded.    

Well documented.

## [Neo4jGraphMakingTests](https://gitfront.io/r/MathieuSeraphim/MhUK1nEM1jHT/Neo4jGraphMakingTests/)

Linked to the Antimony project; for uploading video data as a graph on Neo4j.    

Not documented at all.

## [Tellurium](https://gitfront.io/r/MathieuSeraphim/8zCRHUw2fa7W/Tellurium/)

Project for detecting faces and other labels in images, regrouping faces into face groups, and linking said face groups with the other labels in one big graph.    
Large project, including four subprojects.    
Modular and more or less well coded.    

Inputs and outputs documented in various README.md files.    

Subprojects:
- [Telluric Acid](https://gitfront.io/r/MathieuSeraphim/PW2fLb9AXRj9/Telluric-Acid/)
- Tellurium Tetrachloride\*
- [Bismuth Telluride](https://gitfront.io/r/MathieuSeraphim/ADSshsum7391/Bismuth-Telluride/)
- [Tellurocysteine](https://gitfront.io/r/MathieuSeraphim/KVo2htemWbQv/Tellurocysteine/)    

\*: *No link for this one, due to the limitations of free GitFront accounts at time of writing.*    
*Tellurium Tetrachloride: image and video labeling module for use as part of the Tellurium project (adapted from the Antimony project).*    
*Feel free to message me if you somehow want access.*    

## [Logo Detection](https://gitfront.io/r/MathieuSeraphim/5fA5a3srwFx3/LogoDetectionReport/)

Last project, unfinished.  
Attempts to create a logo detection model to complement Tellurium.  

The Git repo is a recap of what has been done.
