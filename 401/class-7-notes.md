# Bearer Authorization

1. **What is a JSON Web Token (JWT)?**
   - A JSON Web Token (JWT) is a compact, URL-safe means of representing claims between two parties. It's digitally signed and often used for authentication and information exchange.
  
2. **When should we use JSON Web Tokens?**
   - JSON Web Tokens (JWTs) are commonly used for stateless authentication mechanisms, such as user authentication in web applications and APIs, where sessions are not stored server-side.

3. **Claims are expected in which structural component of a JWT?**
   - Claims are expected in the payload component of a JWT, which is the middle part that contains the actual data (claims) being transmitted.

4. **If I get a JWT and I can decode the payload, how can we call that secure?**
   - Decoding the payload of a JWT doesn't ensure security; however, if the JWT is digitally signed and the signature can be verified, it provides integrity and authenticity, making it secure.

5. **If sending a JWT, what must sender and receiver both know?**
   - Both the sender and the receiver must know the secret key used to sign the JWT in order to verify its authenticity. This secret key is appended in the signature component of the JWT.

6. **Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
   - The concatenated content and secret can be sent to the recruiter through secure channels like encrypted email or secure messaging apps. The recipient must be informed to keep the secret key confidential.

7. **Why use JWT?**
   - JWTs are compact and self-contained, making them efficient for transmitting data between parties. They are also easily verifiable, enabling secure communication without the need for server-side sessions.

8. **JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**
   - JWT's compactness means they can be easily transmitted over networks without excessive overhead. Being self-contained, they carry all necessary information within the token itself, reducing the need for additional server resources.

9. **What are the three components (the structure) of a JWT signature?**
   - The three components of a JWT signature are the header, the payload, and the signature itself. Together, they form the complete JWT structure.
