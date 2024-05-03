# Authentication

1: **Safely Hashing and Storing Passwords**

- To keep passwords secure, we use a hashing algorithm like Bcrypt. This converts the password into a unique string of characters, making it unreadable even if the database is compromised. Additionally, we add salt, a random string, to each password before hashing to prevent attackers from using precomputed hash tables.

2: **Bcrypt Explained**

- Bcrypt is an adaptive hash function designed to be slow and resource-intensive, making it difficult for attackers to brute force passwords. It introduces a work factor that determines how slow the hashing process will be, making it resistant to faster computers in the future.

3: **Why Bcrypt?**

- Bcrypt is preferred over other hashing algorithms like MD5 and SHA because it significantly slows down brute force attacks. By adjusting the work factor, we can ensure passwords remain secure even as computing power increases. This makes Bcrypt a solid choice for securely storing passwords in web applications.

4: **Basic Authentication**

- Basic Authentication is a method for an HTTP user agent to provide a username and password when making a request. It uses the "Authorization" header field in the format "Authorization: Basic <credentials>", where <credentials> is the Base64 encoding of the username and password joined by a colon.

5: **Header Properties in Basic Auth Request**

- The "Authorization" header field is necessary in a Basic Auth request. It contains the encoded credentials in the format "Basic <encoded_credentials>", where <encoded_credentials> is the Base64 encoding of the username and password joined by a colon.

7: **Encoding of Username and Password**

- The username and password in Basic Auth are combined with a colon (:), then encoded into an octet sequence using Base64 encoding. For example, if the username is "Aladdin" and the password is "open sesame", the encoded string is "QWxhZGRpbjpvcGVuIHNlc2FtZQ==".

8: **Define the authentication process to a non-technical recruiter:**

Authentication verifies users' identities through credentials like usernames and passwords, ensuring they are who they claim to be.

9: **How should your error messaging respond (both HTTP and HTML)? Why?**

Error messages should be generic in both HTTP responses and HTML pages to prevent revealing sensitive system details, reducing the risk of exploitation.

10: **Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.**

Link bookmarked. OWASP fundamentals provide vital guidelines for secure authentication implementation, reducing vulnerabilities in applications over their lifecycle.
