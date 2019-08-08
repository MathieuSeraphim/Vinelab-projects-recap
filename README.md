# Vinelab projects recap

From May to August 2019, I was an intern at Vinelab, in Beirut, Lebanon. I worked primarily on the research and development of Machine Learning solutions for Social Media analysis. Here is a quick recap of all my GitHub repositories linked to this internship, in chronological order.

Keep in mind that as I am still in training, these projects may not be ideal in terms of code clarity or documentation.

## InstagramInfluencerFakeFollowerProportion

https://github.com/MathieuSeraphim/InstagramInfluencerFakeFollowerProportion

My attempt to use a classification model to determine Instagram bots or "fake" followers.

It is more a recap of my actions and conclusions than a real project, though.

It is well documented.

## ImageLabelExtractor

https://github.com/MathieuSeraphim/ImageLabelExtractor

Uses the ResNet50 image classifier, trained on the ImageNet dataset and included in Keras, to classify images and extract the five best labels (classifications for the image), with their corresponding confidence scores.

Intended as a test projects, just to see if it works.

Includes no documentation.

## VideoLabelExtractor

https://github.com/MathieuSeraphim/VideoLabelExtractor

Same as above - but takes a video as argument, and divides it into multiple images (one per scene) before analysis.

## LabelProject

https://github.com/MathieuSeraphim/LabelProject

Given an Instagram public account, scrapes any amount of images that you want and extracts their label using ResNet50, before exporting all the data gathered in a JSON file.

A fully standalone and well documented project. I'm pretty proud of it.

## Mask_RCNN

https://github.com/MathieuSeraphim/Mask_RCNN

Another test, this time using an image segmentation model trained on Microsoft's COCO dataset.

Again, no documentation to speak of.

## ObjectDetector_crude

https://github.com/MathieuSeraphim/ObjectDetector_crude

A kind-of-messy adaptation of the TensorFlow pretrained models API. This time, the model is ResNet V2, trained with a subset of Google's Open Images dataet, for the purpose of object detection.

Contains a lot of unnecesary documents, in many ways inferior to the next repository.

It is however functional, and will output images with bounding boxes, which the next repository does not do.

Somewhat documented.

## ObjectDetectorAndLabeler

https://github.com/MathieuSeraphim/ObjectDetectorAndLabeler

Same as above, but more standalone, and returns only labels. Also, *cleaner*.

Well documented.

## Antimony

https://github.com/MathieuSeraphim/Antimony

Project for scraping and labeling images an videos.

Modular and more or less well coded.

Well documented.

## Neo4jGraphMakingTests

https://github.com/MathieuSeraphim/Neo4jGraphMakingTests

Linked to the Antimony project; for uploading video data as a graph on Neo4j.

Not documented at all.

## Tellurium

https://github.com/MathieuSeraphim/Tellurium

https://github.com/MathieuSeraphim/Telluric_Acid

https://github.com/MathieuSeraphim/Tellurium_Tetrachloride

https://github.com/MathieuSeraphim/Bismuth_Telluride

https://github.com/MathieuSeraphim/Tellurocysteine

Project for detecting faces and other labels in images, regrouping faces into face groups, and linking said face groups with the other labels in one big graph.

Large project, including four subprojects.

Modular and more or less well coded.

Inputs and outputs documented in various README.md files.
