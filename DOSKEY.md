# Doskey

[Doskey](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/doskey) can be used to create aliases for programs in Windows.

Example `.doskey.bat`:
```
@echo off

DOSKEY rider="C:\Program Files\JetBrains\Jet Brains Rider 2021.3.2\bin\rider64" $*
```

A registry key can be added to run `.doskey.bat` whenever any command prompt is opened up.

`REG ADD "HKLM\Software\Microsoft\Command Processor" /v AutoRun /t REG_SZ /d %Home%\.doskey.bat`
