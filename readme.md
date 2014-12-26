Codeception Mailcatcher Module
==============================

### Configuration

To use the Mailcatcher module, it must be enabled and the following configurations adjusted.

To enable the module for acceptance test, the file acceptance.suite.yml must be modified.

```yml
    enabled:
        - ...
        - MailCatcher
    config:
        MailCatcher:
            url: 'https://mailcatcher.example.dev'
            port: '443'
```