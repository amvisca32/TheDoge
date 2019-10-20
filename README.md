# RITSEC CTF: the_doge

**Category:** Forensics
**Points:** 100
**Description:**

> Stegnography is the practice of concealing messages or information within other nonsecret text or data. The doge holds the information
you want, feed the doge a _treat_ to get the hidden message.

## Write-up

The passphrase: treat

```bash
$ steghide extract -sf the_doge.jpg
Enter passphrase: 
wrote extracted data to "doge_ctf.txt".
```

```bash
$ steghide extract -sf the_doge.jpg -xf <outputFile>
Enter passphrase: 
wrote extracted data to "output.txt".
```
