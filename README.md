[![Toulouse Blacklist Mirror](https://github.com/NethServer/toulouse-bl-mirror/actions/workflows/toulouse-bl-mirror.yml/badge.svg)](https://github.com/NethServer/toulouse-bl-mirror/actions/workflows/toulouse-bl-mirror.yml)

# :flying_saucer: Toulouse Blacklist Mirror :flying_saucer:

### Simple :robot: Github Workflow :robot: that sync `Toulouse` blacklists for `ufdbGuard` 

These are the actions that will be performed on schedule :

- Check if a new version of the blacklist has been released comparing the [MD5](http://dsi.ut-capitole.fr/blacklists/download/MD5SUM.LST)
- If `MD5` does not match, download the new blacklist :fr: [Blacklists UT1](https://dsi.ut-capitole.fr/blacklists/index_en.php) :fr:
- Check if the download has been successful comparing the `MD5`
- Commit to the repo
