# how-to-use-private-repository

## HTTPS

1. Make personal access token
    - `setting -> Developer settings -> Personal access tokens`
    - [attension]
        - Even if you had made it before, it might be expired. Then, you should recreate it.

2. Make private repository on Giuhub web page.

3. Clone the private ripository.

4. Setting the git config to use private repository.
    - set the personal access token.
        - `git config --add --local url."https://<Personal access token>:x-oauth-basic@github.com/".insteadOf "https://github.com/"`
