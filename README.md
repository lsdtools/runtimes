# LSD runtimes

Signed LSD runtimes (Base and Desktop) that `lsdtools setup` downloads.

Each release is one runtime version (`base-1.0.0`, `desktop-1.0.0`, ...), and each file is named by its sha256.
lsdtools checks every file against https://lsd.tools' signed manifest before installing it, and falls back to
https://lsd.tools when a file here is missing or does not match.

Install with `pip install lsdtools`, then `lsdtools setup`.
