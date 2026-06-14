# scoop-bucket

This is the official Scoop bucket for [JugaadLang](https://github.com/JugaadLang/jugaadlang).

## Installation

To add this bucket to Scoop and install JugaadLang, run the following commands in PowerShell:

```powershell
# Add the JugaadLang bucket
scoop bucket add jugaadlang https://github.com/JugaadLang/scoop-bucket.git

# Install JugaadLang
scoop install jugaadlang
```

*(Note: If there is a naming conflict with another bucket, you can install it explicitly using `scoop install jugaadlang/jugaadlang`.)*

## Usage

After installation, the `jug` command will be available in your command line:

```powershell
jug --version
```
