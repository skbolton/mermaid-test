# mermaid-test

```mermaid
flowchart TD
    user[User]--->account_check{Has Account?}
    account_check -- Yes --> do_sign_in[Sign in]
    account_check -- No --> create[Create Account]
    do_sign_in --> team_check{Has Team?}
    team_check -- Yes --> show_dashboard(Show dashboard)
    team_check -- No --> show_signup(Show Signup)
```
