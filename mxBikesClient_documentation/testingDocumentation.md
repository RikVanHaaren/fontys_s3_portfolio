# 🚧 Testing Documentation
I just read about this concept and want to add it to the project.

## Table of contents
- [1. Introduction](#1-Introduction)
- [1. Test Plan](#1-Test-Plan)
- [1. Test Cases](#1-Test-Cases)

## 1. Introduction

## 2. Test Plan

## 3. Test Cases
| Test Case   ID | Test Case Description | Test Steps | Test Data | Expected Results | Actual Results | Pass/Fail |
|---|---|---|---|---|---|---|
| 1 | Check user login with valid data | 1. Go to the site   'https://localhost:3000'<br>     2. Click 'Sign In' (top right) <br>     3. Enter Email<br>     4. Enter Password<br>     5. Click 'continue' | Email=test@test.com<br>     Password=Pa$$word! | User should login into the   application<br>     and the button 'Sign in' changed to <br>     'Sign Out'. |  |  |
| 2 | Check user login with invalid   data | 1. Go to the site   'https://localhost:3000'<br>     2. Click 'Sign In' (top right) <br>     3. Enter Email<br>     4. Enter Password<br>     5. Click 'continue' | Email=not@user.com<br>     Password=Pa$$word! | User should not login into the   application<br>     and the user will get an message that filled credentials do not exist. |  |  |
| 3 | Check user can logout | 1. Go to the site   'https://localhost:3000'<br>     2. Click 'Sign Out' (top right)  |  | User should login into the   application<br>     and the button 'Sign Out' changed to 'Sign in'. |  |  |
| 4 | Check user can add comment | 1. Go to the site   'https://localhost:3000'<br>     2. Login as a user<br>     3. Click on 'ItemStore' (left next to icon)<br>     4. Click on a 'Item' <br>     5. Fill text in 'comment' input<br>     6. Click on 'Post comment' | Text=Hello | The comment 'Text' should appear   on <br>     the bottom of the comment section. |  |  |
| 5 | Check user can't add empty   comment | 1. Go to the site   'https://localhost:3000'<br>     2. Login as a user<br>     3. Click on 'ItemStore' (left next to icon)<br>     4. Click on a 'Item' <br>     5. Fill text in 'comment' input<br>     6. Click on 'Post comment' | Text= | The comment should not have   appear on the bottom of the comment section and the user should get notifed. |  |  |
| 6 | Check user can edit a comment | 1. Go to the site   'https://localhost:3000'<br>     2. Login as a user<br>     3. Click on 'ItemStore' (left next to icon)<br>     4. Click on a 'Item' <br>     5. Select a created comment<br>     6. Edit field to 'Text'<br>     7. Click on 'Update' | Text=New text | The comment 'Text' should appear   on <br>     the bottom of the comment section. |  |  |
| 7 | Check user can delete a comment | 1. Go to the site   'https://localhost:3000'<br>     2. Login as a user<br>     3. Click on 'ItemStore' (left next to icon)<br>     4. Click on a 'Item' <br>     5. Select a created comment<br>     6. Click on 'Delete'<br>     7. Click on 'Confirm' |  | The selected comment should be   removed from the comment section. |  |  |
| 8 | Check user can download a mod | 1. Go to the site   'https://localhost:3000'<br>     2. Click on 'ItemStore' (left next to icon)<br>     3. Click on a 'Item' <br>     4. Click on 'Download' |  | The mod should be download on   your<br>     local pc. |  |  |
| 9 | Check user can subscribe to a   mod | 1. Go to the site   'https://localhost:3000'<br>     2. Login as a user<br>     3. Click on 'ItemStore' (left next to icon)<br>     4. Click on a 'Item' <br>     5. Click on 'Subscribe' |  | The button 'Subscribe' should   changed<br>     to 'Remove Subsciption' and the a toast<br>     message should popup on the local <br>     machine. The mod should be found in<br>     the directory on the pc. |  |  |
| 10 | Check user can remove subscribe   from a mod | 1. Go to the site   'https://localhost:3000'<br>     2. Login as a user<br>     3. Click on 'ItemStore' (left next to icon)<br>     4. Click on a 'Item' <br>     5. Click on 'Remove Subscription' |  | The button 'Remove   Subsciption'  should changed   'Subscribe'  and the a toast message   should popup on the local machine. The mod should be removed from the   directory on the pc. |  |  |