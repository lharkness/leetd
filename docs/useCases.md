## Use Cases ##

### User Management ###

1. New User wants to register with the site.  New user clicks "Register".  New User is prompted for their email address, user name, security question and asked if they want the default set of contexts.  The system will send the new user a temporary password (good for 30 minutes) and the user will need to log in and change that password.  The system will store a hash of that password and optionally generate the default contexts.
2. Existing user needs to reset their password.  Existing user will click the "forgot password" link.  The system will send them a temporary password and the existing user will log in and change their password.  The system will store a hash of that password.
3. Existing user no longer has access to their email and has forgotten their password.  