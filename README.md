## New york times news application 

This is a simple swift application using the New york times API to pull the most popular artciles in the last 30 days. 
It shows a list of 20 most popular articles and when you click on the article it showws the article details. (Master/ Detail)

## Getting started

1. Make sure you running the latest XCode on your machine
2. Download the NYNewsArticlesAPI files from the repository 
3. Open the files in Xcode 
4. Run the NYNewsArticlesAPI Scheme
5. Will open your simulator and display the News articles in a list format

## Running Tests

NYNewsArticleAPI can be tested using the built in framework XCTest

1. Click on the project drop down
2. Click on test
3. Navigate to your report navigator in Xcode 
4. Click on the latest tests ran and click on Covearge 
5. This will show a testing report for the app as well as the code coverage

## Architecture

![Uploading figure-model-view-viewmodel-1.jpg…]()

NYNewsArticleAPI is implemented using MVVM architecture pattern 

1. Model represents the data model 
2. View represents the user interface 
3. View-Model: Is where the logic sits that gets passed to the controller which talks to the user interface (View)

## Structure

"Views" -> Where the list view and the detail views sit
"Extensions" -> TableView extension to register the NIB
"Network manager" -> Files that relate to the API Calls

## API

1: Using the NY Times Most Popular Articles API
2: Using swifts URLSession to make the API calls 
