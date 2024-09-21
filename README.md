# zzlss 🛠️

**zzlss** is a customized, intelligent `ls` replacement designed to make your file system browsing more efficient and visually organized. With support for sorting directories, files, symlinks, and hidden files into distinct categories, `zzlss` offers a streamlined and flexible way to view your file system contents. The name `zzlss` follows a personalized utility prefix system, ensuring it’s easy to identify among your tools.

## Features ✨
- **Organized output**: Automatically sorts and displays directories, files, symlinks, and hidden files separately.
- **Customizable view**: Toggle between various views, including visibility of section separators and headers.
- **Highly efficient**: Perfect for quick file system browsing on macOS with specialized sorting.
- **Lightweight**: Pure shell scripting for speed and simplicity.
- **Easy integration**: Drop-in replacement for your everyday `ls` needs with the added power of enhanced sorting and grouping.

## Installation 🚀

1. **Clone the repository**:
   ```bash
   git clone https://github.com/walkerjian/zzlss.git
   ```
2. **Move `zzlss` to your `~/bin` or `/usr/local/bin`**:
   ```bash
   cp zzlss ~/bin/   # or /usr/local/bin/
   ```
3. **Make the script executable**:
   ```bash
   chmod +x ~/bin/zzlss   # or wherever you placed the script
   ```

4. **Update your shell profile** (if `~/bin` isn’t in your `$PATH`):
   - Add this line to your `.zshrc`, `.bash_profile`, or equivalent:
     ```bash
     export PATH="$HOME/bin:$PATH"
     ```
   - Reload your shell:
     ```bash
     source ~/.zshrc  # or equivalent
     ```

## Usage 📖

Run `zzlss` as you would with `ls`:
```bash
zzlss
```

### Options
- **`--no-seps`**: Hide section separators.
- **`--no-headings`**: Suppress section headers.

Example:
```bash
zzlss --no-seps --no-headings
```

## Contributing 🤝

Feel free to open issues or submit pull requests! All contributions are welcome.

### To Do:
- Add more sorting categories.
- Improve performance for large directories.
- Support additional file attributes.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙌

This project was inspired by the need for a more organized and customizable file browsing experience, and it continues to grow thanks to feedback and contributions.
