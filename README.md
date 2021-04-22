# Road to "Verified" commit

## Don't forget "Signing commits"

```bash
git commit -S -m commit message
```

or

```
git config --global commit.gpgsign true
git commit -m commit message
```

## For Windows Environment

```
git config --global gpg.program "C:\Program Files (x86)\GnuPG\bin\gpg.exe"
```

