## Unreleased

## v0.3.0 (March 23rd, 2021)

FEATURES:

* Proxy server mode: The extension now starts a Vault API proxy at
  `http://127.0.0.1:8200` [[GH-27](https://github.com/hashicorp/vault-lambda-extension/pull/27)]
  * **Breaking change:** The extension no longer writes its own Vault auth token
    to disk. Writing pre-configured secrets to disk remains unchanged.

## v0.2.0 (January 20th, 2021)

IMPROVEMENTS:

* Add Vault IAM Server ID login header if set. [[GH-21](https://github.com/hashicorp/vault-lambda-extension/pull/21)]
* quick-start: Make db_instance_type configurable.

## v0.1.0 (October 8th, 2020)

Features:

* Initial release
