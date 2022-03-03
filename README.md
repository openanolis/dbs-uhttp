# db-uhttp

This is a minimal implementation of the
[HTTP/1.0](https://tools.ietf.org/html/rfc1945) and
[HTTP/1.1](https://www.ietf.org/rfc/rfc2616.txt) protocols. This HTTP
implementation is stateless thus it does not support chunking or compression.


## Acknowledgement

db-uhttp is forked from Fireckracker's [micro-http](https://github.com/firecracker-microvm/micro-http). And we switch from the usage of vmm-sys-util::Poll to MIO in order to support cross-platform compatibility such as macOS.

The micro-http implementation is used in production by Firecracker.

## Contributing

To contribute to db-uhttp, checkout the
[contribution guidelines](CONTRIBUTING.md).

## Releases

New db-uhttp versions are released via the GitHub repository releases page. A
history of changes is recorded in our [changelog](CHANGELOG.md).

## Policy for Security Disclosures

If you suspect you have uncovered a vulnerability, contact us privately, as
outlined in our [security policy document](); we will immediately prioritize
your disclosure.