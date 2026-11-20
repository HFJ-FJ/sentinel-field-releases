# Replay app release policy

User authorized policy, 2026-11-20.

After each requested app update is built and verified, publish its signed APK and replay-update.json together. Retain the current org.sentinel.replay APK and the two preceding releases in the current repository tree. Remove older APKs for this package after the new release is verified. Preserve other package channels. Use increasing versionCode and the same signing key. Verify public manifest, download hash and signature, and refresh CDN manifest caches. Do not rewrite Git history. Report phone-specific verification limits.
