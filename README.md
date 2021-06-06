# My public PGP key

You can download my public PGP key here. You can also find it on various keyservers. Using `gnupg` on Mac/Linux:
```
$ gpg --recv-keys 25465CC0AAEE4CE8D8FCDB54B12CC2C92A66F144
```

The output of `$ gpg --list-key 25465CC0AAEE4CE8D8FCDB54B12CC2C92A66F144` should match the following:
```
pub   rsa4096/0xB12CC2C92A66F144 2021-05-03 [C]
      Key fingerprint = 2546 5CC0 AAEE 4CE8 D8FC  DB54 B12C C2C9 2A66 F144
uid                   [ultimate] the_4n0nym0u53 <anonymous71@protonmail.com>
sub   rsa4096/0x166428DFE743D152 2021-05-03 [S] [expires: 2022-05-03]
sub   rsa4096/0xE5F58813C1FF0009 2021-05-03 [E] [expires: 2022-05-03]
sub   rsa4096/0xE220CBBE43C3C0F8 2021-05-03 [A] [expires: 2022-05-03]
```
