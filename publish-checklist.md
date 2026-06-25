# Publish Checklist

Current phase: safe starter appcast only.

Before any live update is advertised:

- Generate Sparkle signing material outside this repository and outside the app source project.
- Put only the Sparkle public key in the app bundle.
- Build a versioned EnergyTagger DJ release archive.
- Sign the archive with Sparkle tools.
- Generate an appcast that includes a valid signature.
- Run a packaged-app update test.
- Confirm real-library tag writing remains blocked.
- Confirm Serato crate modification remains blocked.

Do not upload app ZIPs, music files, Serato files, secrets, tokens, certificates, or signing keys during this starter feed phase.
