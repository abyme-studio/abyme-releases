# abyme-releases

abyme's built binaries, one release per deployed commit. Nothing else lives here: no source.

Install abyme on a Mac with Apple silicon or Linux on x86_64:

    curl -fsSL https://abyme.dev/install.sh | sh

Each release holds `manifest.json` (the commit and each archive's size and SHA-256) and one
`<target>.tar.gz` per platform (`aarch64-macos`, `x86_64-linux`), each holding `abymed` and
`abyme`. The latest release is the build the hosted gateway runs.
