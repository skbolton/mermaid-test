# mermaid-test

```mermaid
flowchart TD
    user[User]--->account_check{Has Account?}
    account_check -- Yes --> do_sign_in[Sign in]
    account_check -- No --> create[Create Account]
    create ---> do_sign_in
```
