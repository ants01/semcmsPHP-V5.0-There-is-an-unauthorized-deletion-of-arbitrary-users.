# semcmsPHP-V5.0-There-is-an-unauthorized-deletion-of-arbitrary-users.
Local setup: Add a user in the backend user management module, then delete the user. Use Burp Suite to capture the request and clear the cookies for testing. When there are no cookies (i.e., unauthorized status), the user can still be deleted — indicating an unauthorized user deletion vulnerability.
