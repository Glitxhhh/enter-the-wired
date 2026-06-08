# Enter the Wired

> plug in. install. disappear.

Minimal Linux installer for ACCELA and SLSsteam.

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/ciscosweater/enter-the-wired/main/enter-the-wired | bash
```

## ACCELA

This repository maintains an actively developed fork of ACCELA. Builds are
published as [GitHub Releases](https://github.com/ciscosweater/enter-the-wired/releases).
The installer downloads the latest release automatically, or uses a local
`ACCELA*.tar.gz` if one is found alongside the script.

I know people talk shit about ACCELA. This fork is actually maintained now —
open an [issue](https://github.com/ciscosweater/enter-the-wired/issues)
with suggestions or fixes and we'll sort it out.

## Scripts

- `enter-the-wired` installs everything
- `accela` installs or updates ACCELA
- `fix-deps` fixes missing system dependencies
- `uninstall` removes installed components

## Fix issues

```bash
curl -fsSL https://raw.githubusercontent.com/ciscosweater/enter-the-wired/main/fix-deps | bash
```

## Credits

- **Deadboy666** — Headcrab (h3adcr-b)
- **AceSLS** — SLSsteam

## Repo

https://github.com/ciscosweater/enter-the-wired

> no noise. no bloat. just works.
