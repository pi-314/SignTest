# SignTest
This is just a test repo, which is subjected to be deleted at any time. You are strongly advised to NOT use this repository, unless you have a reason to do so ;)

First change (CLI sign.)

Second change (VSC sign.)

Third change (CLI sig.)

Fourth change (VSC sig)

$ gpg --edit-card
Reader ...........: Yubico YubiKey OTP FIDO CCID
Application ID ...: D2760001240100000006259260450000
<....output skipped...>

gpg/card> admin
Admin commands are allowed

gpg/card> passwd
# <--- At this step pinentry-mac will ask you to enter your Admin PIN (PUC)
gpg: OpenPGP card no. D2760001240100000006259260450000 detected

1 - change PIN
2 - unblock PIN
3 - change Admin PIN
4 - set the Reset Code
Q - quit
Your selection? 2

# <--- At this step pinentry-mac will ask you (twice) to enter the new PIN
PIN unblocked and new PIN set.

1 - change PIN
2 - unblock PIN
3 - change Admin PIN
4 - set the Reset Code
Q - quit

Your selection? Q

gpg/card> q

Lorem ipsum