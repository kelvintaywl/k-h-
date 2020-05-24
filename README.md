# kōhī

:coffee:

> In Japan, coffee is pronounced as kōhī (コーヒー).

This is a toy [Protobuf](https://developers.google.com/protocol-buffers) project with coffee-related definitions.

The Coffee model is nothing fancy; Please do not shoot me down with [third-wave coffee](https://en.wikipedia.org/wiki/Third_wave_of_coffee) philosophies :bow:


The goal is to have automated CI builds to push published definitions to various packages in different languages:

- Python
- Ruby
- Javascript

## Validation

We use [Buf](https://buf.build/) to handle Protobuf definition validation.
> Install the CLI: https://buf.build/docs/installation

```sh
buf check lint
```
