# semcmsPHP-V5.0-There-is-an-unauthorized-deletion-of-arbitrary-users.
Local setup: Add a user in the backend user management module, then delete the user. Use Burp Suite to capture the request and clear the cookies for testing. When there are no cookies (i.e., unauthorized status), the user can still be deleted — indicating an unauthorized user deletion vulnerability.
<img width="2870" height="1611" alt="poc1" src="https://github.com/user-attachments/assets/fbe37262-e38c-40c1-943d-aeba15cadc65" />
<img width="2534" height="1184" alt="poc2" src="https://github.com/user-attachments/assets/0e4e0482-d91e-4ba3-a338-555032f202b4" />
<img width="2879" height="1507" alt="poc3" src="https://github.com/user-attachments/assets/c1879ca1-3d21-496c-ae9e-5fcd8efcbad6" />
