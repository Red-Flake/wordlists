# Wordlists Repo

This repository contains a curated collection of wordlists commonly used for security testing, password cracking, and other research purposes. It’s designed to be used both directly and as a flake input for Nix overlays.

<br>

## Repository Contents

- **rockyou**  
  The popular rockyou password list.

- **statistically-likely-usernames Submodule**  
  This repository integrates [statistically-likely-usernames](https://github.com/insidetrust/statistically-likely-usernames) as a Git submodule to provide a comprehensive collection of additional username wordlists.

- **SecLists Submodule**  
  This repository integrates [SecLists](https://github.com/danielmiessler/SecLists) as a Git submodule to provide a comprehensive collection of additional wordlists.  

- **Security-Wordlist Submodule**
  This repository integrates [Security-Wordlist](https://github.com/DragonJAR/Security-Wordlist) as a Git submodule to provide a comprehensive collection of additional wordlists.  

<br>

## Getting Started

**Clone the Repository with Submodules:**
```bash
git clone --recursive https://github.com/yourusername/wordlists.git
```

<br>

## Updating the submodules
```bash
git submodule update --remote
```