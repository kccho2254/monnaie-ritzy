# project-two

To make the database automatically:
sequelize db:create
<!-- To create a branch:
$ git checkout -b theBranchName
To see all branches:
$ git branch
To switch in and out of different branches:
$ git Checkout      whatever branch you want to hop into


To push changes to your branch:

$ git add .
$ git commit -m ""
$ git push origin -u <branch-name>

Create pull request in Github


To add pulled code from main branch to different branch

$ git pull origin main

 Delete in github repository
    $ git push --delete origin <branch-name>
Delete locally
    $ git branch -D <branch-name> -->

Add "name" to database
Make id's update so that the first is 1, second is 2, etc.
Make Budget Categories appear on api/user_data
    Let users pick and choose their own default categories to add to Budget Categories
Test put routes

Default wedding categories
Add custom wedding categories
Add budget line item

Budget Line Item must have the category ID corresponding to Budget Categories (which must be populated by either new budget catgories or existing preset categories)


Estimated budget
    what you want to spend

Actual budget
    what you end up spending

    Add a category
        delete button
        edit button
    Add a budget item
        delete button
        edit button

When you add a budget line item you have to select a budget category which has a foreign key to categories

Budget Category
    List of budget line items


Line is the actual estimate

Bar is the estimated/expected cost