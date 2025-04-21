# app_dev_2
Second submission of the app development journal for BUSN 208, Spring 2025.

**Overview: You'll find two apps within this submission**

### App #1: "semantic_analysis"
This app fulfills the core requirements of the assignment (to create an app that contains 2 coreML models)
**TAB #1**
CoreML Model: MNIST (Single Digit Recognition)
Purpose: Convert four independent single-digit inputs to integer values. Then, multiply the two-digit number formed by the upper two digits (e.g. 7+3=73) by the the two-digit number formed by the lower two digits into a single integer value.
Input: Drawings
Output: Integers

**TAB #2**
CoreML Model: YOLOv3 (Object Detection)
Purpose: Enter an image and view an itemized list of what it contains.
Input: Image
Output: List of contents
Notes: This has been notoriously buggy on the default pictures of plants that are loaded into the native iOS simulators, so there may be issues in testing. 

### App #2: "second_ml_app"
This app extends the core requirements by adding a third coreML model.

**TAB #1**
CoreML Model: MobileNetV2 (Object Recognition)
Purpose: Enter an image and receive a single output of what the object contains, as well as an emoji (from a limited set) and a level of confidence.
Input: Image
Output: Single item
