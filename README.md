# R00t-Shell 🛡️

R00t-Shell is a comprehensive PHP-based mini file manager designed to offer extensive administrative capabilities. It is built with security in mind, providing users with the necessary tools to manage their server files efficiently. **Please note that this tool should be used responsibly and only on systems you have explicit permission to administer. Unauthorized use is illegal.**

## Features 🌟

- **File Management:** Easily navigate, upload, delete, rename, touch (update modified date), and edit files.
- **Directory Structure:** Browse through directories with a user-friendly interface.
- **WordPress Integration:** Retrieve detailed information about WordPress installations including site URL, admin email, database details, and more. Create new administrator users for your WordPress sites.
- **Security Measures:**
  - Login Protection: Access is restricted to authenticated users only via a password-protected login.
  - Secure Password Storage: The login password is hashed using MD5 (for demonstration purposes, please use stronger hashing in production environments).
- **User-Friendly Interface:** A clean and intuitive design with dark mode for better visibility.

## Installation 🔧

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/R00t-Shell.git
   ```
2. **Navigate to the Directory:**
   ```bash
   cd R00t-Shell
   ```
3. **Set the Login Password:**
   - Modify the `$hashedPassword` variable in the PHP code to your desired password hash.
4. **Place the Script on Your Server:**
   - Upload `R00t-Shell.php` to a directory on your server where you want to manage files.

## Usage 🎨

1. **Access the Shell:**
   - Open your web browser and navigate to `http://yourserver.com/path/to/R00t-Shell.php`.
2. **Login:**
   - Enter the password `R00t` at the login prompt.
3. **Navigate through Directories:**
   - Use the breadcrumb navigation or parent directory button to move between directories.
4. **File Operations:**
   - **Upload Files:** Select and upload files via the "⬆️ Upload" button.
   - **Delete Files/Directories:** Click the 🗑️ Delete button next to a file or directory.
   - **Rename Files/Directories:** Use the ✏️ Rename option.
   - **Edit Files:** Click on the 📄 File to open it in an editor for editing.
   - **Update Modified Date:** Enter a new date and click 💲 Update.

5. **WordPress Features:**
   - If your directory contains a `wp-config.php`, you can retrieve WordPress information by clicking the 🌐 WordPress Info button.
   - **Create Admin Users:** Use the 👤 Create Admin option to add new administrator users for your WordPress installation.

## Security Note ⚠️

R00t-Shell is intended for educational and authorized use. Unauthorized access or misuse of this tool can lead to security breaches and legal consequences. Always ensure that you have the appropriate permissions before using R00t-Shell on any server.

## Contributing 🤝

Contributions are welcome! If you find bugs, have suggestions for new features, or improve the code in any way, please feel free to create a pull request.

1. Fork the repository.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## License 📝

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Remember, with great power comes great responsibility. Use this tool wisely and legally.**

Happy Coding! 🚀
