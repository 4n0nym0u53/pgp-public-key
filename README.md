# My public PGP key

My public PGP key's fingerprint is: `2546 5CC0 AAEE 4CE8 D8FC DB54 B12C C2C9 2A66 F144`

You can download my public PGP key from this repository [here](https://raw.githubusercontent.com/theanonymousexyz/pgp-public-key/main/the_4n0nym0u53.asc). You can also find it on various keyservers, e.g. [`keys.openpgp.org`](https://keys.openpgp.org/vks/v1/by-fingerprint/25465CC0AAEE4CE8D8FCDB54B12CC2C92A66F144). The easiest method is to import it with your favorite PGP program. Here's how to do it using `gpg` on Mac/Linux:
```
$ gpg --recv-keys 25465CC0AAEE4CE8D8FCDB54B12CC2C92A66F144
```

The output of `$ gpg --list-key 25465CC0AAEE4CE8D8FCDB54B12CC2C92A66F144` should match the following:
```
pub   rsa4096/0xB12CC2C92A66F144 2021-05-03 [C]
      Key fingerprint = 2546 5CC0 AAEE 4CE8 D8FC  DB54 B12C C2C9 2A66 F144
uid                   [ unknown] the_4n0nym0u53 <anonymous71@protonmail.com>
sub   rsa4096/0x166428DFE743D152 2021-05-03 [S] [expires: 2022-05-03]
sub   rsa4096/0xE5F58813C1FF0009 2021-05-03 [E] [expires: 2022-05-03]
sub   rsa4096/0xE220CBBE43C3C0F8 2021-05-03 [A] [expires: 2022-05-03]
```
