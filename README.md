# Postale

Postale is a simple module that wraps `smtplib` and `email` libraries. It is configured in order to make it easy to create a new mail, and setup attachments, body, etc.

## Installation

```sh
pip install postale
```

## Usage

### Import it

You can either
```python
import postale
```
or
```python
from postale import Mail
```

As for now, `Mail` is the only class in this module.

### Create an e-mail

The following table shows the arguments that the class `Mail` can receive.

Argument      | Type                 | Optional | Default
------------- | -------------------- | -------- | -------
`host`        | `str`                | No       | -
`port`        | `int`                | Yes      | `587`
`sender`      | `str`                | Yes      | `None`
`recipients`  | `str`,`list`,`tuple` | Yes      | `None`
`subject`     | `str`                | Yes      | `None`
`body`        | `str`                | Yes      | `None`
`attachments` | `str`,`dict`         | Yes      | `None`

### Printing

### Edit an e-mail

### Sending
