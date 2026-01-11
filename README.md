# pos — Short alias for Positron (Windows)

This repository provides a tiny convenience alias for the Positron (Posit) CLI on Windows.

## What this is
- Two files are included in this repo: `pos` and `pos.cmd`.
- They act as a short alias (`pos`) that invokes the full `positron` command on Windows.

## Installation

1. Locate your Positron installation's `bin` directory. Common locations on Windows include:

   - `C:\Program Files\Positron\bin`
   - `C:\Program Files (x86)\Positron\bin`
   - The `bin` folder next to wherever you installed Positron

2. Copy both files from this repository into that `bin` directory:

   - `pos`
   - `pos.cmd`

3. If you installed Positron for all users, you may need administrator rights to copy into `Program Files`.

## Usage

- Open a new terminal (so PATH is refreshed) and run `pos` to invoke Positron.
- On Windows the `pos.cmd` wrapper ensures `pos` works from Command Prompt / PowerShell.

## Notes & Troubleshooting
- If `pos` is not recognized, ensure the Positron `bin` directory is present on your PATH and you opened a new terminal after copying the files.
- If you have execution policy restrictions, run PowerShell as Administrator or adjust policies as needed.
- The `pos` file is intended to be the short, POSIX-style command; `pos.cmd` is the Windows wrapper.

## Contributing
- This repo is intentionally minimal. If you want alternate shells or behavior, modify or add wrapper scripts and test locally.

## License
- No license file is included. Copy and use these files as you need; add a LICENSE if you want explicit terms.

## Files
- `pos` — short alias script
- `pos.cmd` — Windows command wrapper
