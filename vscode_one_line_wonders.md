
# VS Code One-Line Wonders

A collection of 50 one-liners to enhance your workflow in Visual Studio Code (VS Code).

```bash
# 1. Open a specific file
code myfile.txt

# 2. Open the current folder in VS Code
code .

# 3. Install an extension directly from the terminal
code --install-extension ms-python.python

# 4. List all installed extensions
code --list-extensions

# 5. Uninstall a VS Code extension
code --uninstall-extension ms-python.python

# 6. Diff two files side-by-side
code --diff file1.txt file2.txt

# 7. Open VS Code without extensions
code --disable-extensions

# 8. Search for text in the current folder
code . -g 'searchText'

# 9. Open VS Code with a specific file and go to a specific line and column
code -g myfile.txt:15:10

# 10. Launch a new VS Code window
code --new-window

# 11. Open a file and highlight specific text
code -g myfile.txt:5

# 12. Print help for VS Code CLI commands
code --help

# 13. Check the current VS Code version
code --version

# 14. Open multiple files at once
code file1.txt file2.txt file3.txt

# 15. Install multiple extensions at once
code --install-extension ms-python.python ms-vscode.cpptools

# 16. Uninstall multiple extensions at once
code --uninstall-extension ms-python.python ms-vscode.cpptools

# 17. Open a folder in a new VS Code window
code --new-window myfolder/

# 18. Force reload the VS Code window
code --force

# 19. Open VS Code with a temporary user data directory
code --user-data-dir ./tempuserdata

# 20. Start VS Code in a specific language
code --locale=en

# 21. Restore the default user settings
rm -rf ~/.config/Code/User/settings.json && code .

# 22. List extensions along with their versions
code --list-extensions --show-versions

# 23. Generate a list of installed extensions into a file
code --list-extensions > extensions.txt

# 24. Open VS Code in a specific folder with a specific profile
code --profile dev-profile --folder-uri /path/to/folder

# 25. Export the installed extensions for reuse
code --list-extensions | xargs -L 1 echo code --install-extension > extensions.sh

# 26. Open a remote project using SSH
code --folder-uri vscode-remote://ssh-remote+hostname/path/to/project

# 27. Sync settings across devices
code --sync enable

# 28. Show logs for VS Code extension development
code --log trace

# 29. Open VS Code with administrative privileges
sudo code .

# 30. Start a live server extension
code --folder-uri live-server:/

# 31. Open a file as read-only
code --read-only myfile.txt

# 32. Disable telemetry reporting
code --disable-telemetry

# 33. Open a specific workspace
code myworkspace.code-workspace

# 34. View workspace settings
cat .vscode/settings.json

# 35. Open a specific settings file in VS Code
code ~/.config/Code/User/settings.json

# 36. Create a new empty file in VS Code
touch newfile.txt && code newfile.txt

# 37. Open VS Code in fullscreen mode
code --maximized .

# 38. Switch to a specific theme
code --extensions-dir ~/.vscode/extensions && code --locale=en

# 39. Enable experimental features
code --enable-proposed-api extension-id

# 40. Open a specific URL in VS Code
code --folder-uri https://github.com/microsoft/vscode

# 41. Create a new notebook file
code --new-notebook notebook.ipynb

# 42. Launch VS Code with Git integration disabled
code --disable-git

# 43. Open a specific file with a workspace folder
code --folder-uri file:///path/to/workspace --file-uri file:///path/to/file

# 44. Open a file in preview mode
code --preview file.txt

# 45. Open the Extensions view directly
code --open-view extensions

# 46. Open the Problems view directly
code --open-view problems

# 47. Open a new untitled file in VS Code
code --new-window untitled:

# 48. Start debugging a specific file
code --debug file.js

# 49. Open a specific folder as a workspace
code --add folder1/ folder2/

# 50. Create a symbolic link to use VS Code from any terminal
ln -s /Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code /usr/local/bin/code
```
