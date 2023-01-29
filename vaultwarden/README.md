# VaultWarden

Vaultwarden is a server and a alternative backend for the password manager Bitwarden. 
While Vaultwarden is used with the Bitwarden clients it does not implement the same feature set as the Bitwarden server. However, the setup is much simpler.

<img src="https://macandegg.b-cdn.net/wp-content/uploads/2021/02/bitwarden-logo.png">


### Additional environment

| Name                    | Description                                                            | Value               |
| ----------------------- | ---------------------------------------------------------------------- | ------------------- |
| `ADMIN_TOKEN`           | The admin token used for /admin                                        | `R@ndomToken$tring` |
| `WEBSOCKET_ENABLED`     | Enables websocket notifications                                        | `false`             |
| `SIGNUPS_ALLOWED`       | Controls if new users can register                                     | `true`              |
| `SIGNUPS_DOMAINS_WHITELIST`| List of domain names for users allowed to register                  | `1c.ru, 2t.com`     |
| `SIGNUPS_VERIFY`        | Whether to require account verification for newly-registered users.    | `true`              |
| `SHOW_PASSWORD_HINT`    | Whether a password hint should be shown in the page.                   | `false`             |







## Project links
[Bitwarden](https://bitwarden.com)

[GitHub Vaultwarden](https://github.com/dani-garcia/vaultwarden)
