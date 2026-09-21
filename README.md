# Ordinal

Downloads for the Ordinal desktop app. Get it at [ordinalcomputer.com](https://ordinalcomputer.com).

- Windows: [Ordinal-Setup.exe](https://github.com/Ordinal-Computer/releases/releases/latest/download/Ordinal-Setup.exe)
- Mac (Apple Silicon): [Ordinal-Mac.dmg](https://github.com/Ordinal-Computer/releases/releases/latest/download/Ordinal-Mac.dmg)

## Opening on Mac

The Mac app isn't signed with an Apple Developer ID yet, so macOS calls it "damaged". Drag Ordinal into Applications, run this once in Terminal, then open it:

```
xattr -cr /Applications/Ordinal.app
```

This clears the "downloaded from the internet" flag.

The source lives in private repos; this repo only holds releases.
