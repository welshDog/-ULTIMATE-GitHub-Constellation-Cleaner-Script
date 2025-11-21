# 🧹 ULTIMATE GitHub Constellation Cleaner Script

![Status](https://img.shields.io/badge/status-active-brightgreen)
![BROski](https://img.shields.io/badge/BROski♾-ADHD%20Powered-blueviolet)
![Python](https://img.shields.io/badge/python-3.7+-blue)
![License](https://img.shields.io/badge/license-MIT-green)

> **One script to clean them all.** Auto-tidy your entire GitHub constellation in minutes.

## 🚀 What This Does

This Python script automatically cleans and organizes **ALL your GitHub repositories** with zero manual work:

✅ **Auto-descriptions** - Adds friendly placeholders to repos with missing descriptions  
✅ **Auto-READMEs** - Generates professional README files with status badges  
✅ **Topic tagging** - Auto-tags repos with `adhd`, `neurodivergent`, `hyperfocus-zone`  
✅ **Archive old/inactive repos** - Auto-archives repos with 12+ months of inactivity  
✅ **Secret scanning** - Basic pattern check for exposed API keys, tokens, passwords  
✅ **Status badges** - Adds visual badges to all auto-generated READMEs  

## 💥 Why You Need This

- **61 repos?** Clean them in 5 minutes.
- **Missing descriptions?** Fixed automatically.
- **No READMEs?** Generated with your branding.
- **Old test projects?** Archived and out of the way.
- **Accidentally exposed secrets?** Flagged for review.

## 🛠️ Installation

```bash
# Install PyGithub
pip install PyGithub
```

## 🔑 Setup Your GitHub Token

1. Go to [GitHub Settings > Developer Settings > Personal Access Tokens](https://github.com/settings/tokens)
2. Generate a new token (classic) with `repo` scope
3. Set it as an environment variable:

```bash
export GITHUB_TOKEN="your_token_here"
```

Or edit the script and paste it directly in `GITHUB_TOKEN`.

## ⚡ Usage

```bash
python ULTIMATE-Constellation-Cleaner-Script
```

**That's it!** The script will:
1. Connect to your GitHub account
2. Loop through all repos
3. Add descriptions where missing
4. Generate READMEs for repos without them
5. Tag repos with neurodivergent-friendly topics
6. Archive repos inactive for 12+ months
7. Scan for exposed secrets and flag them
8. Print a full summary report

## 📊 What You'll See

```
🚀 BROski Constellation Cleaner starting...
Found 61 repositories to clean!

[1/61] 🔍 hypercode
 ✓ README exists
 ✅ Added topics: neurodivergent, adhd

[2/61] 🔍 old-test-repo
 ✅ Added description
 ✅ Added README.md with status badge
 📦 Last updated 18 months ago - archiving...

[3/61] 🔍 config-project
 🚨 SECRET ALERT:
  ⚠️ Potential secret in config.py

=============================================================
🎉 BROski Constellation Cleaning COMPLETE!
=============================================================
📝 Descriptions added: 15
📄 READMEs created: 12
🏷️ Repos tagged: 45
📦 Repos archived: 8
🚨 Potential secrets found: 2

✨ Your constellation is looking SHARP, BROski! ✨
```

## 🎨 Customization

Edit these variables in the script to customize behavior:

```python
# Change the default description
DEFAULT_DESC = "Your custom description here"

# Change archive threshold (in months)
ARCHIVE_AFTER_MONTHS = 12

# Edit the README template in create_readme() function
```

## 🔐 Security Features

The script includes basic secret detection for:
- API keys
- Secret keys  
- Passwords
- Bearer tokens
- GitHub personal access tokens (`ghp_...`)
- OpenAI keys (`sk-...`)

**Note:** This is a basic pattern check. For production apps, use [GitHub Advanced Security](https://github.com/features/security) or [git-secrets](https://github.com/awslabs/git-secrets).

## 🌟 Part of the BROski Ecosystem

This script is part of the **Hyperfocus Zone** constellation - a suite of neurodivergent-friendly development tools.

- 🧠 [HyperCode Language](https://github.com/welshDog/hypercode)
- 🎯 [ULTIMATE Hyperfocus Constellation](https://github.com/welshDog/ULTIMATE-HYPERFOCUS-CONSTELLATION)
- 🏪 [Hyperfocus Zone Shop](https://hyperfocuszone.myspreadshop.co.uk/)
- 💬 [Discord Community](https://discord.gg/yourlink)

## 📜 License

MIT License - See [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Built with ADHD-powered hyperfocus! PRs, issues, and feedback welcome.

## 💜 Support

If this script saved you hours of manual work:
- ⭐ Star this repo
- 🍴 Fork it and customize
- 🛍️ Check out the [Hyperfocus Zone merch](https://hyperfocuszone.myspreadshop.co.uk/)
- ☕ [Buy me a coffee](https://buymeacoffee.com/yourlink) (optional)

---

**Made with 💜 by [BROski♾](https://github.com/welshDog)**  
*Auto-tidying GitHub, one constellation at a time.*
