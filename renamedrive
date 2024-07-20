SETLOCAL ENABLEDELAYEDEXPANSION

begin:

ren \\%1\c$\windows\system32\drivers\crowdstrike\c-00000291*.sys c-00000291*.bad
if !errorlevel! equ 0 (
    Echo "%1 Success"
    exit 0
goto begin
