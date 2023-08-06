# Assignment given by Property Angel, as mentioned in property-angel_assignment.pdf file.

## Basically the task/assignment was to create a simple web app using zoho creators platform.
1. The app should consist of a form that needs certain felids of various types such as text, date, radio boxes etc. Now I made the choice to include radio and select type.
2. Then the task mentioned to create 5 widgets using zoho creator widgets [creator-api-for-widgets](https://www.zoho.com/creator/newhelp/app-settings/widgets/creator-api-for-widgets.html#updaterecord) which are basic api's with very basic documentation.
3. One widget should be used to fetch all records, another one to create new record, one to delete and one to update and lastly one widget to fetch records using some id.


## I have completed the assignment, by completing following steps
1. successfully created zoho creator account.
2. successfully crated a basic app and added 20 mentioned records.
3. successfully developed and tested all required widgets to satisfy assignment needs.

### Points to remember: 
-  zoho creator app along with all widgets will be hosted on zoho domains for just 15 days starting from 05/08/2023.
-  I hvae spent lot of time in designing the app and widgets, only bare minimum design is used.

## How to use this app?
1. The app is hosted at [https://creatorapp.zoho.in/vipul55491/students/](https://creatorapp.zoho.in/vipul55491/students/), again this won't be permanent.
2. This repo consists of folders ending with -page in names, those directories contains the code for those specific widgets.

## Packeting a widget from directories.
1. Rename the directory ending with -page in name to app.
2. Navigate to this repo path in terminal.
3. If zet is installed then use command `zet validate` to validate first and then `zet pack` to create a .zip package.
4. Now this .zip file has to uploaded on zoho creator under widget, to be used as a page in zoho creator.

## References
1. The widgets project directory was initialized using zoho-extension-toolkit more can be found [here](https://www.zoho.com/creator/newhelp/app-settings/widgets/install-cli.html)
2. A sample widget to try and test out in zoho creator can be found [here](https://help.zoho.com/portal/en/kb/creator/developer-guide/application-settings/widgets/articles/sample-widget#Sample_Widget_Playground)
3. Documentation on initializing widget repo with zet can be fount [here](https://www.zoho.com/creator/newhelp/app-settings/widgets/create-a-widget.html)