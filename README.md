
# Plymouth XP Theme

### Description

**Plymouth XP Theme** is a Plymouth boot theme inspired by the classic Windows XP boot screen. It brings a nostalgic touch to your Linux boot process with a design that closely mimics the iconic Windows XP loading screen.

### Features

- **Classic Windows XP Design**: Emulates the look and feel of the Windows XP boot screen.
- **Smooth Animation**: Includes a progress bar animation similar to the original XP boot.
- **Easy Installation**: Simple to set up and configure.

### Installation

1. **Download the Theme**:
   - Clone or download the theme files from the repository.

2. **Copy to Plymouth Themes Directory**:
   ```bash
   sudo cp -r plymouth-xp-theme /usr/share/plymouth/themes/
   ```

3. **Update Plymouth Theme**:
    Set the Plymouth theme to `plymouth-xp-theme`:
    ```bash
    sudo plymouth-set-default-theme -R plymouth-xp-theme
    ```

4. **Update Initramfs**:
   ```bash
   sudo update-initramfs -u
   ```

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

### Contributing

Feel free to fork this project and submit pull requests. All contributions are welcome!

### Pull Requests

We welcome pull requests! If you have suggestions for improvements or new features, please fork the repository and submit a pull request. Contributions from the community help make this project better for everyone.

### Credits

- Inspired by the original Windows XP boot screen.
- Created by FraioVeio
