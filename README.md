### Bragg.cs.miami.edu

Logging into bragg requires either
- password and a TOTP (Time-based One Time Password) authenticator
- or ssh public-private key pair.

The TOPT authenticator can be google authenticator, Yubikey 5C, or other device implementing the [TOTP protocol](https://www.rfc-editor.org/rfc/rfc6238).

The configurable parameters are, 
- Time based
- SHA-1
- 6 digits
- 30 seconds
and these are the defaults for Google Authenticator (and most other devices).

To create or renew your google authenticator, run `google-authenticator`.

Lab machines are listed in [Bromelia-names](https://github.com/csc-department/info/blob/main/csc-colors-names-map.pdf) PDF. These will only require a password or a public-private key pair.

