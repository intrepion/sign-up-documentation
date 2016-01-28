# Use Case - Sign Up

 - Name: Sign Up
 - Summary: A new user signs up.
 - Rationale: While using the website, many new users find that they cannot sign in without signing up.
 - Users: All new users
 - Preconditions: A new user is not signed up.
 - Postconditions: A new user is signed up.

Basic Course of Events

1. New user clicks on Sign Up.
1. New user types a username.
1. New user types an email.
1. New user types a password and confirmation.
1. New user checks the agreement box.
1. New user submits the Sign Up form.
1. System creates user.
1. System sets user to disabled.
1. System sets user verfication code.
1. System sets user verification expiration time.
1. System sends user an email with verification link.
1. New user finds email and clicks the verification link.
1. System sets user to enabled.
1. System gives user a role.
1. System brings user to the Sign In page.

Alternative Paths

1. New user clicks on Sign Up.
1. New user types a username.
  1. The username is blank.
    1. System notifies the new user that the username is required.
  1. The username is already in the system.
    1. System notifies the new user to sign in or use a different username.
1. New user types an email.
  1. The email is blank.
    1. System notifies the new user that the email is required.
  1. The email is already in the system.
    1. System notifies the new user to sign in or use a different email.
1. New user types a password and confirmation.
  1. The password or confirmation is blank.
    1. System notifies the new user that the password and confirmation are required.
  1. The password and confirmation do not match.
    1. System notifies the new user to type in the password and confirmation correctly.
1. New user checks the agreement box.
  1. The agreement is not agreed to.
    1. System notifies the new user that the agreement is required.
1. New user submits the Sign Up form.
1. System creates user.
1. System sets user to disabled.
1. System sets user verfication code.
1. System sets user verification expiration time.
1. System sends user an email with verification link.
1. New user finds email and clicks the verification link.
  1. The verification link has expired.
    1. System deletes the new user.
    1. The new user is asked to sign up again.
  1. The verification code is incorrect.
    1. System notifies the new user that the verfication code is incorrect.
1. System sets user to enabled.
1. System gives user a role.
1. System brings user to the Sign In page.
