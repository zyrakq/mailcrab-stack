# Using

```sh
curl smtp://127.0.0.1:1025 --mail-from myself@example.com --mail-rcpt receiver@example.com --upload-file normal.email
```

With TLS:

```sh
curl --ssl-reqd smtps://mailcrab.local:1025 --mail-from myself@example.com --mail-rcpt receiver@example.com --upload-file normal.email
```

```sh
curl --ssl-reqd smtps://mailcrab.local:1025 --mail-from myself@example.com --mail-rcpt receiver@example.com --upload-file normal.email --user 'user:pass'
```

Insecure:

```sh
curl -k --ssl-reqd smtps://mailcrab.local:1025 --mail-from myself@example.com --mail-rcpt receiver@example.com --upload-file normal.email --user 'user:pass'
```
