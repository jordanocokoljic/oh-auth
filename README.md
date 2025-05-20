# Oh, Auth!

A simple web page for preparing the URL for beginning the OAuth 2.0
authorization code grant flow.

It offers an easy to use form for providing the necessary parameters. It also
provides a random generation utility built on the Web Crypto API for the
`state` and code verifier.

In addition, the verifier can also be encoded with SHA-256 if this is required
by the selected `code_challenge_method`.

Currently, no validation of parameters is done - this is planned.
