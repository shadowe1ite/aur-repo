# e1ite AUR Repository

A custom Arch Linux User Repository containing prebuilt and maintained AUR packages for easier installation with **paru**.

## Usage

Add this repository to your `paru.conf` (usually located at `~/.config/paru/paru.conf`):

    [e1ite]
    Url = https://github.com/shadowe1ite/aur-repo/
    GenerateSrcinfo

Then, update and sync the new repository database:

    paru -Sya --noconfirm

Once added, you can fetch and install packages directly from this repository using:

    paru -S <package-name>

## Available Packages

- **dicebear** – DiceBear avatar library  
- **govarnam-schemes-git** – Schemes for the Govarnam transliteration engine  
- **pdf-parser** – PDF analysis tool  
- **peepdf** – PDF analysis and malware detection utility

---

Maintained with ❤️ by [shadowe1ite](https://github.com/shadowe1ite)
