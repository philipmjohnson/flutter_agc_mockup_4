# Flutter mockup of the Agile Garden Club app (Phase 4)

This repository contains the fourth increment of work on a mockup of the [Agile Garden Club](https://agilegardenclub.com) application.

The main changes in this version are:

* Reorganization of the project directory structure to conform to the "Riverpod Architecture" as discussed in [Flutter Project Structure: Feature-first or Layer-first](https://codewithandrea.com/articles/flutter-project-structure/).

* For this mockup, the Riverpod Provider declarations are in the "Application" layer/directories. The DB classes are in the "Domain" layer/directories. There is no "Repository" layer. 

## Screen shots

Here are screen shots that illustrate current application state. We use the flutter_markdown package to provide information on what should appear in a page when we haven't gotten around to actually mocking up the contents.

Click on any screen shot to see it full-size.

### Splash, signin, and signup pages:

<p style="text-align: center">
  <img src="./README-screenshots/splash.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/signin.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/signup.png" width="30%">
</p>

### Home page: My News, My Gardens, My Discussions

<p style="text-align: center">
  <img src="./README-screenshots/home-my-news.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/home-my-gardens.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/home-my-discussions.png" width="30%">
</p>

### Navigation Drawer, Gardens, and Chapters pages

<p style="text-align: center">
  <img src="./README-screenshots/drawer.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/gardens.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/chapters.png" width="30%">
</p>

### Add Garden and Edit Garden

<p style="text-align: center">
  <img src="./README-screenshots/add-garden.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/edit-garden.png" width="30%">
</p>

### Outcomes, Seeds, Members pages

<p style="text-align: center">
  <img src="./README-screenshots/outcomes.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/seeds.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/members.png" width="30%">
</p>

### Discussions page

<p style="text-align: center">
  <img src="./README-screenshots/discussions.png" width="30%">
</p>

### Help

<p style="text-align: center">
  <img src="./README-screenshots/help.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/help-local.png" width="30%">
</p>


## Installation

This app can only be run locally in development mode. To install and run:

* Clone this repository to your computer.
* Bring up an IDE such as IntelliJ on the repository.
* Run the app within a simulator.

## DartDoc

Unfortunately, `dart doc` does not yet provide useful documentation for this mockup, since almost all of the code resides in the `src` directory.  This should be addressed soon, see <https://github.com/dart-lang/dartdoc/issues/3096>.
