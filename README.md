# My public PGP key

My public PGP key's fingerprint is: `FFFD 8602 E0E9 E6D9 E30E  EBEE DFD3 9F41 2054 CB84`

You can download my public PGP key from this repository [here](https://raw.githubusercontent.com/theanonymousexyz/pgp-public-key/main/pgp.asc). You can also find it on various keyservers, e.g. [`keys.openpgp.org`](https://keys.openpgp.org/vks/v1/by-fingerprint/FFFD8602E0E9E6D9E30EEBEEDFD39F412054CB84). The easiest method is to import it with your favorite PGP program. Here's how to do it using `gpg` on Mac/Linux:
```
$ gpg --recv-keys FFFD8602E0E9E6D9E30EEBEEDFD39F412054CB84
```

The output of `$ gpg --list-key --with-fingerprint --keyid-format long FFFD8602E0E9E6D9E30EEBEEDFD39F412054CB84` should match the following:
```
pub   rsa4096/DFD39F412054CB84 2021-10-23 [C] [expires: 2023-10-23]
      Key fingerprint = FFFD 8602 E0E9 E6D9 E30E  EBEE DFD3 9F41 2054 CB84
uid                 [ unknown] the_4n0nym0u53 <hello@theanonymouse.xyz>
sub   rsa4096/35EE09F5481049BB 2021-10-23 [S] [expires: 2022-04-21]
      Key fingerprint = C661 6D73 2E95 FBCC 6C18  ACF4 35EE 09F5 4810 49BB
sub   rsa4096/CC2CF61DF936F387 2021-10-23 [E] [expires: 2022-04-21]
      Key fingerprint = E456 FDDA 64C0 498A 25F7  5ED8 CC2C F61D F936 F387
sub   rsa4096/066A075F72C4C11A 2021-10-23 [A] [expires: 2022-04-21]
      Key fingerprint = 4631 A129 FFDA 244C 018D  B13F 066A 075F 72C4 C11A
```
