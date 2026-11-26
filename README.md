# duet transfer

Files shared with the Claude duet agent.

## eXplorist_GC_2_15_Install.exe (split)

Split into 95 MB parts in `parts/`. To rejoin:

PowerShell:
    cmd /c copy /b parts\eXplorist_GC_2_15_Install.exe.part* eXplorist_GC_2_15_Install.exe

bash:
    cat parts/eXplorist_GC_2_15_Install.exe.part* > eXplorist_GC_2_15_Install.exe

Then verify against `parts/SHA256.txt` (sha256).
