# mdBook + GitHub Pages Test Environment

This project uses [Nix](https://nixos.org/) for reproducible development environments.

## Getting Started

1. **Install Nix** (if not already installed):
   See https://nixos.org/download.html

2. **Enter the development shell:**
   ```bash
   nix develop
   ```
   This will provide you with `mdbook`, `cargo`, and `git`.

3. **Build the book:**
   ```bash
   mdbook build
   ```

4. **Serve the book locally:**
   ```bash
   mdbook serve
   ```

---

All dependencies are managed by Nix. No need to install anything globally.
