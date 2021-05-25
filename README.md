# CARE4THER APP USING ML AND ANDROID 

Nearly 80% of accidents take place yearly. this piece of code will help the users to detect an accident at an early stage and it is detected by different libraries like Deep learning etc.

## Code Requirements

You can install Conda for python which resolves all the dependencies for machine learning.

pip install requirements.txt
## Procedure
* Run create_dataset.py for converting the video to images.
* Then run main.py to train the model.
* Finally, run model.py for testing your model.

The Algorithm:
Each video is a set of individual images that are time-dependent sequences. The algorithm - a hierarchical recurrent neural network - can treat each video as a time-dependent sequence, but still, allows each video to be an independent data point.

The algorithm uses two layers of long short-term memory neural networks. The first neural network (NN) is a recurrent network that analyzes the time-dependent sequence of the images within each video. The second takes the encoding of the first NN and builds a second NN that reflects which videos contain accidents and which do not. The resulting model enables a prediction of whether new dashcam footage has an accident.

Through this method, the HRNN incorporates a time-dependent aspect of the frames within each video to predict how likely it is a new video contains a car accident.


*VARIOUS TECHNOLOGIES USED IN THE PROJECT*

1. DEEP LEARNING
2. MACHINE LEARNING
3. ANDROID
4. JAVA
5. CNN

*Why this project is important*

To prevent accidents, this is the app that can tell the location of the accident and it could prevent the accidents.


*FEATURES OF THE APP*

The app is made using Java language, various features are being added in the app like.. alert system for an accident, sensors,etc	The app is made using Java language, various features are being added in the app like.. alert system for an accident, sensors,etc


Try implementing this project and suggest changes:)	Try implementing this project and suggest changes:)
Happy Learning!	Happy Learning!

## Roadmap
 - [x] Create android project
 - [ ] Integrate ML model into app.
 - [ ] Create App Design.
 - [ ] Add getUserlocation feature.
 - [ ] Add option to add/edit/view emergency contacts.
 - [ ] Fetch nearby hospital's information using Google Maps API.
 - [ ] Use hardware sensors to detect motion of vehicle.

## Features
|   **Feature**          | **Description**                                                   | **Status**         |
|------------------------|-------------------------------------------------------------------|--------------------|
| Predict accident       | Predict accident prone areas using ML model                       | :heavy_check_mark: | 
| Home Screen            | Show User's location, SOS button, Show emergency contacts         | :x:                |
|                        |                                                                   |                    |


## How to set up the Android app in your development environment

### Development Setup

Before you begin, make sure you have the Android Studio SDK downloaded and set up correctly. You can find a guide here: [Setting up Android Studio](http://developer.android.com/sdk/installing/index.html?pkg=studio)

### Setting up the Android Project

1. Download the Care4ther- project source either by forking and cloning the repository (recommended if you want to contribute) or by downloading it as a ZIP file and extracting it.

2. Open Android Studio, you will see a **Welcome to Android** window. Under Quick Start, select _Import Project (Eclipse ADT, Gradle, etc.)_

3. Navigate to the directory where you saved the Care4ther- project, select the "Care4ther-/Care4therApp" folder, and hit OK. Android Studio should now begin building the project with Gradle.

4. Once this process is complete and Android Studio opens, check the Console for any build errors.

5. Once all build errors have been resolved, you should be all set to build the app and test it.

6. To Build the app, go to _Build>Make Project_ (or press the Make Project icon in the toolbar).

7. After the app is built successfully, you can test it by running it on either a real device or an emulator by going to _Run>Run 'app'_ or pressing the Run icon in the toolbar.

If you want to build apk only, go to Build>Build apk and apk would be built, and the directory, where apk is generated, would be prompted by Android Studio.

## Contributions Best Practices

### Code practices

Please help us follow the best practice to make it easy for the reviewer as well as the contributor. We want to focus on the code quality more than on managing pull request ethics.

 * Single commit per pull request (So that commit history doesn't become messy)
 * Reference the issue numbers in the commit message. Follow the pattern ``` Fixed #<issue number> <commit message>```
 * Follow uniform design practices. The design language must be consistent throughout the app.
 * The pull request will not get merged until and unless the commits are squashed. In case there are multiple commits on the PR, the commit author needs to squash them and not the maintainers cherrypicking and merging squashes.
 * If the PR is related to any front-end change, please attach relevant screenshots in the pull request description.

#### How to `git squash`?

As a tip for new developers who struggle with squashing commits into one, multiple commits may appear in your pull request mostly due to the following reasons.

 * Intentionally adding multiple commit messages after each change without just `git adding.
 * Updating the current branch with the remote so a merge commit takes place.

You can also follow this easy and helpful tutorial: [How to squash commits](https://www.youtube.com/watch?v=viY1BbKZhSI&ab_channel=StudyZone)
Despite any reason, follow the steps given below to squash all commits into one adhering to our best practices.

 * Setup remote to upstream branch if not set before;

`$ git remote add upstream https://github.com/unnati914/Care4ther-.git`

 * Check into the branch related to the pull request

`$ git checkout <branch-name>`

 * Perform a soft reset to retain the changes while removing all the commit details

`$ git reset --soft upstream/main`

 * Add files to the staging area

`$ git add <file paths or "." to add everything>`

 * Create a new commit with a proper message following commit message guidelines

`$ git commit -m "tag: commit message"`

 * If you have already made a pull request,

`$ git push -f origin <branch-name>`

### Code style

Please try to follow the mentioned guidelines while before submitting your code so that a uniform code style is maintained in the project. It also makes it easier for the reviewer and other developers to understand.

 * While naming the layout files, ensure that the convention followed is (activity/fragment) _ (name).xml like ```activity_main.xml```, ```fragment_user_location.xml```.
 * * The activity/fragment file name corresponding to the layout files should be named as                       (activity/fragment name)(activity/fragment).java like ```UserLocationActivity.java``` corresponding to the layout file ```activity_user_location.xml```, ```UserLocationFragment.java``` corresponding to the layout file ```fragment_user_location.xml```.
 * Name the views and widgets defined in the layout files as (view type/widget) _ (name) _ (no. in the file if any) like  ```button_save```, ```editText_user_location```.

### This Project is associated to 
[<img src="https://crosswoc.ieeedtu.in/images/imgcw.png" width = "400px">](https://crosswoc.ieeedtu.in/)

## Project Maintainer 

<table>
  <tbody><tr>
    <td align="center"><a href="https://github.com/unnati914"><img alt="" src="https://avatars.githubusercontent.com/u/69121168?s=400&u=adfcc6a4636b47497032e87a609cc003ec9c63c8&v=4" width="130px;"><br><sub><b>
 Unnati </b></sub></a><br><a href="" title="Code">💻 </a></td></a></td>
  </tr>
</tbody></table>
