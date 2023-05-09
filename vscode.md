
# VS Code setup

Install the following extensions:

    # install the ms-vscode-remote.remote-wsl extension 
    # https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl
    code --install-extension ms-vscode-remote.remote-wsl
    # Python:
    code --install-extension ms-python.python

## R

To get R setup, find your R installation directory on Windows, from
RStudio:

![](https://user-images.githubusercontent.com/122299965/237078941-ead3eb08-bc40-4a8a-a96d-2111088e9547.png)

Add the following to settings.json in VS Code:

        "r.rterm.windows": "C:\\Program Files\\R\\R-4.2.2\\bin\\x64\\R.exe",
        "r.rpath.windows": "C:\\Program Files\\R\\R-4.2.2\\bin\\x64\\R.exe",

https://stackoverflow.com/questions/72707869/changing-r-version-in-vs-code
