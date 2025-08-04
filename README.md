# Windows Wallpaper Saver

A simple and practical Windows wallpaper automatic saving tool that helps you collect and save daily beautiful wallpapers.

## 🚀 Quick Start

### System Requirements

- Windows 10/11

### How to Use

1. **Download and Run**
   - Simply double-click `WallpaperSaver.exe` to run
   - No installation required

2. **Choose Save Location**
   When the program starts, you'll see three options:
   ```
   1.Copy to current directory
   2.Copy to 'C:\Users\[Username]\Pictures\Wallpapers'
   3.Specify a path
   ```
   
   - **Option 1**: Saves wallpaper to the same folder as the exe file
   - **Option 2**: Saves to your Pictures/Wallpapers folder (recommended)
   - **Option 3**: Choose your own custom folder

3. **Automatic Processing**
   - The program will automatically extract your current Windows wallpaper
   - Save it with a timestamp filename like: `wp-25-08-04-836817.png`
   - Check for duplicates to avoid saving the same wallpaper twice

## 🌟 Features

- 🖼️ **Auto Extract Current Wallpaper**: Extract the currently set wallpaper from Windows system
- 📅 **Timestamp Naming**: Automatic naming with date and time for easy management
- 🔍 **Duplicate Detection**: Smart detection of duplicate wallpapers to avoid saving identical images
- 📁 **Flexible Save Locations**: Support multiple save path options
- 🛡️ **Error Handling**: Comprehensive error handling mechanism to ensure stable operation
- 💻 **No Dependencies**: Standalone executable.

## 📖 Usage Examples

### Basic Usage
1. Double-click `WallpaperSaver.exe`
2. Type `1` and press Enter (to save in current directory)
3. Done! Your wallpaper is saved

### Save to Pictures Folder
1. Double-click `WallpaperSaver.exe`
2. Type `2` and press Enter
3. Your wallpaper is saved to `C:\Users\[YourName]\Pictures\Wallpapers\`

### Custom Location
1. Double-click `WallpaperSaver.exe`
2. Type `3` and press Enter
3. Enter your desired path (e.g., `D:\MyWallpapers\`)
4. Your wallpaper is saved to the specified location

## 🔧 How It Works

1. **Read System Wallpaper**: Extract from `%APPDATA%\Microsoft\Windows\Themes\TranscodedWallpaper`
2. **Hash Verification**: Calculate file hash using SHA256
3. **Duplicate Detection**: Compare with existing files to avoid duplicates
4. **Safe Saving**: Use temporary files to ensure safe saving process

## 📄 License

This software is licensed for **Personal Use Only** - see the [LICENSE](LICENSE) file for details

**Important**: This software is for personal, non-commercial use only. Commercial use, distribution, or modification for redistribution is not permitted.

## 🙏 Support

If you encounter any issues:
1. Make sure you have a wallpaper set in Windows
2. Try running as administrator if you get permission errors
3. Check that your chosen save location has write permissions

---

⭐ Enjoy collecting your beautiful wallpapers!
