*write-qr-code.ps1*
================

This PowerShell script writes "Hello World" as QR code to the console output.

Parameters
----------
```powershell
PS> ./write-qr-code.ps1 [<CommonParameters>]

[<CommonParameters>]
    This script supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, WarningAction, 
    WarningVariable, OutBuffer, PipelineVariable, and OutVariable.
```

Example
-------
```powershell
PS> ./write-qr-code

```

Notes
-----

Related Links
-------------
https://github.com/fleschutz/PowerShell

Script Content
--------------
```powershell

Write-Host "                         " -foregroundColor black -backgroundColor white
Write-Host "  ▄▄▄▄▄▄▄ ▄ ▄▄▄ ▄▄▄▄▄▄▄  " -foregroundColor black -backgroundColor white
Write-Host "  █ ▄▄▄ █ ▄▄▀█  █ ▄▄▄ █  " -foregroundColor black -backgroundColor white
Write-Host "  █ ███ █ █▀ ▄▀ █ ███ █  " -foregroundColor black -backgroundColor white
Write-Host "  █▄▄▄▄▄█ ▄▀█▀█ █▄▄▄▄▄█  " -foregroundColor black -backgroundColor white
Write-Host "  ▄▄▄▄  ▄ ▄▄▄██▄  ▄▄▄ ▄  " -foregroundColor black -backgroundColor white
Write-Host "  ▀ █ ▀▄▄▀█▀▀█▀█▀█▀▀▀▄█  " -foregroundColor black -backgroundColor white
Write-Host "  ▄▄██▀▀▄▄█ ▄▀▄▄▄▀ ▀ ▀▄  " -foregroundColor black -backgroundColor white
Write-Host "  ▄▄▄▄▄▄▄ ▀▀██▄▄██▄ ▀ ▀  " -foregroundColor black -backgroundColor white
Write-Host "  █ ▄▄▄ █  ▀▄ ▄▀ ▀ ██▀▀  " -foregroundColor black -backgroundColor white
Write-Host "  █ ███ █ █▄  ▄ ▀▄ ▀█▀   " -foregroundColor black -backgroundColor white
Write-Host "  █▄▄▄▄▄█ █▀▄█ ███▀ ▄ ▀  " -foregroundColor black -backgroundColor white
Write-Host "                         " -foregroundColor black -backgroundColor white

exit 0 # success
```

*(generated by convert-ps2md.ps1 using the comment-based help of write-qr-code.ps1 as of 09/01/2023 17:51:58)*