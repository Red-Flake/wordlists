# Wordlists Repo

This repository contains a curated collection of wordlists commonly used for security testing, password cracking, and other research purposes. It’s designed to be used both directly and as a flake input for Nix overlays.

<br>

## Repository Contents

- **rockyou**  
  The popular rockyou password list.

- **jsmith.txt & jsmith2.txt**  
  wordlists from statistically-likely-usernames.

- **SecLists Submodule**  
  This repository integrates [SecLists](https://github.com/danielmiessler/SecLists) as a Git submodule to provide a comprehensive collection of additional wordlists.  

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