# Use Case - Reset Password

 - Name: Reset Password
 - Summary: A user resets their password.
 - Rationale: If a user has forgotten their password, they need a way to reset it.
 - Users: All users
 - Preconditions: A user's password isn't reset.
 - Postconditions: A user's password is reset.

Basic Course of Events

1. User clicks on Sign In.
1. User clicks on Reset Password.
1. User fills in their username.
1. User submits form.
1. System sets user verfication code.
1. System sets user verification expiration time.
1. System sends user an email with verification link.
1. User finds email and clicks the verification link.
1. User types a password and confirmation.
1. User submits form.
1. System brings user to the Sign In page.

Alternative Paths

1. User clicks on Sign In.
1. User clicks on Reset Password.
1. User fills in their username.
1. User submits form.
1. System sets user verfication code.
1. System sets user verification expiration time.
1. System sends user an email with verification link.
1. User finds email and clicks the verification link.
  1. The verification link has expired.
    1. System notifieds the User to reset password again.
  1. The verification code is incorrect.
    1. System notifies the new user that the verfication code is incorrect.
1. System brings user to the Change Password page.
1. User types a password and confirmation.
  1. The password or confirmation is blank.
    1. System notifies user that the password and confirmation are required.
  1. The password and confirmation do not match.
    1. System notifies user to type in the password and confirmation correctly.
1. User submits form.
1. System notifies the user that the password has been reset.
1. System brings user to the Sign In page.
