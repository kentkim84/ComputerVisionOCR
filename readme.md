## Purpose
This document provides an overview of the Mobile Application Development 2 Project for Bachelor of Science in Software Development program, including a statement of goals and objectives and a general description of my approach. This working document is directed to my supervisor but should be useful to anyone interested in learning more about creating UWP (Universal Windows Platform) applications. This document is something of an executive summary of the project in its current state and summarise the results in phases.

## Goals and Objectives
My primary mission is to comprehend and develop an implementation that detects multiple characters using OCR (Optical Character Recognition), and then translate the text to another language using Microsoft Azure Cognitive Services.
To achieve this overall objective, I have defined following phases.
* As a part of college project, it can be modified at any convenient time as it't required.
* Phase 1: Make the camera and audio device work.    
* Phase 2: Implement OCR to detect chracters from given source i.e. captured image or image file
* Phase 3: Send request to get which languages supported and detect what language is used in the source
* Phase 4: Send request of translation
* Phase 5: Display the result.

## Challenges and Constraints
* Full integration between UI and Logics
### Apperances of incorrect fragments of UI
Need to choose right layout and design to display correct result.
### Http request errors
Since it uses Azure Cognitive services, network connection is required to use.
### Etc
* Allow camera and audio permission to interact with this application (minimum requirements).
* This application is built based on Microsoft Azure Cognitive services (Text Analysis and Translate Text) with free tier, which means after given packets all used, this application may not respond correctly.

## Running the tests
### Clone
Create a folder, and move into the folder just created, then use git clone command to download a copy of this project
```
$ mkdir folder
$ cd folder
$ git clone https://github.com/kentkim84/ComputerVisionOCR.git
```
### Download
Click [Clone or Download](https://github.com/kentkim84/ComputerVisionOCR), then Click 'Download ZIP'

### Test
Move into the Project folder (VisualTranslator), then run it
```
$ Visual Studion project folder/VisualTranslator
$ run VisualTranslator.sln file
```

## Authors
* **Yongjin Kim** - *Initial work* - [Kentkim84](https://github.com/kentkim84)

## References
* Original Project written by [Damien Costello](damien.costello@gmit.ie)
* [Microsoft OCR Engine class](https://docs.microsoft.com/en-us/uwp/api/windows.media.ocr.ocrengine)
* [Microsoft Text Analytics REST API](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/)
* [Microsoft Text Translate REST API](https://azure.microsoft.com/en-us/services/cognitive-services/translator-text-api/)
