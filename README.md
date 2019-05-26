# Appcenter client build tool
Appcenter client helps you build the mobile apps you and your team are working on.

This interface allows to manage, control and navigate build process for multiple apps on one page. 

## :white_check_mark: General info

To get started, you, or a member of your team, logs into and opens a main form page. In the App's Build Tool page select the desired applications, environment and branch to be built.

Choose **applications**, **environment** and **branch**.

<p align="center">
  <img alt="Main form page" src="https://user-images.githubusercontent.com/29301041/58064876-ed3e9f00-7bd7-11e9-93ec-e716da990261.gif">
</p>

Update the **version** number for app.

<p align="center">
  <img alt="Main form page" src="https://user-images.githubusercontent.com/29301041/58065301-583ca580-7bd9-11e9-8a70-c1e0a84a1d25.gif">
</p>

After clicking the Save and build button the card will be created for the build displaying the current app **Name**, **Display name**, **Environment**, **Version** and **Status**.

You can cancel the build at any time by clicking at the **Cancel** button.

All builds are displayed according to the app operating system: **iOS** and **Android**.

After completion the status will be changed to **Succeeded** or **Failed**.

You can **Download build** or **Download error log**.

<p align="center">
  <img alt="Modal on error" src="https://user-images.githubusercontent.com/29301041/58066037-d8fca100-7bdb-11e9-8c4c-9ce180d236e8.gif">
</p>

List of the latest builds for **master** and **develop** branch to **download (build or error log)** or **distribute**.

**Distribute** the **release** to **distribution groups**.

<p align="center">
  <img alt="Main form page" src="https://user-images.githubusercontent.com/29301041/58059214-2539e800-7bc0-11e9-9e65-c5cd017220b9.gif">
</p>

Login page.

<p align="center">
  <img alt="Main form page" width="800" src="https://user-images.githubusercontent.com/29301041/56873947-52481e80-6a8a-11e9-8f49-fc065a144475.png">
</p>

## :hammer: Technologies
Project is created with:
* React
* AJAX using Axios
* Node.js
* RESTful API

## :arrow_forward: How to Run App

1. cd to the repo
2. Setup
  - run `npm run install`
2. Run 
  - run `npm run start`
