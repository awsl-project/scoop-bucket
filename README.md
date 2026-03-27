# awsl-project Scoop Bucket

Scoop bucket for Windows packages published by awsl-project.

## Install Scoop

If you haven't installed Scoop yet, run the following in **PowerShell**:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex
```

After installation, reopen PowerShell if needed, then verify:

```powershell
scoop --version
```

## Add this bucket

```powershell
scoop bucket add awsl https://github.com/awsl-project/scoop-bucket
```

## Install packages

```powershell
scoop install awsl/maxx
```
