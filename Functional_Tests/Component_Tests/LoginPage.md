**[TC_1]**\
**Title:** [Valid] User with valid credentials should successfully login into system
| Step | Expected Reslt |
| -------- | -------- |
| Navigate to the app | App should be loaded successfully |
| Navigate to the login page | Login page should be loaded successfully |
| Enter valid credentials and click on the 'Login' button | User should successfully login into the app |

**[TC_2]**\
**Title:** [Valid] Registered user should reset password
| Step | Expected Reslt |
| -------- | -------- |
| Navigate to the app | App should be loaded successfully |
| Navigate to the login page | Login page should be loaded successfully |
| Click on the reset password button | Reset password page should be loaded successfully |
| Enter email to the field and click on the 'Reset' button | Successfull password reset message should be appeared |
| Open any email client and check for the reset password email message | Email with instructions should be delivered |

**[TC_3]**\
**Title:** [Valid] User should navigate from the 'reset password' page back to the 'login' page
| Step | Expected Reslt |
| -------- | -------- |
| Navigate to the app | App should be loaded successfully |
| Navigate to the login page | Login page should be loaded successfully |
| Click on the 'Reset password' button | Reset password page should be loaded successfully |
| Click on the 'Back to login page' button | Login page should be loaded successfully |

**[TC_4]**\
**Title:** [InValid] User with invalid credentials should not login into system
| Step | Expected Reslt |
| -------- | -------- |
| Navigate to the app | App should be loaded successfully |
| Navigate to the login page | Login page should be loaded successfully |
| Enter invalid credentials and click on the 'Login' button | Error message should be displayed |

**[TC_5]**\
**Title:** [InValid] Not-registered user should not reset password
| Step | Expected Reslt |
| -------- | -------- |
| Navigate to the app | App should be loaded successfully |
| Navigate to the login page | Login page should be loaded successfully |
| Click on the reset password button | Reset password page should be loaded successfully |
| Enter not-registered email to the field and click on the 'Reset' button | Error message should be appeared with explanation |
| Open any email client and check for the reset password email message | Email with instructions should not be delivered |
