# stealth Scoop bucket

Scoop manifests for [stealth](https://github.com/Will-Barnard-WB/stealth), updated automatically on every release. Don't edit the manifests here: they are generated from the stealth repo.

## Install

1. Install [Scoop](https://scoop.sh).
2. Install Java 21, if you don't have it already:

   ```powershell
   scoop bucket add java
   scoop install java/temurin21-jre
   ```

3. Add this bucket and install stealth:

   ```powershell
   scoop bucket add stealth https://github.com/Will-Barnard-WB/scoop-bucket.git
   scoop install stealth
   ```

Upgrade with `scoop update stealth`.
