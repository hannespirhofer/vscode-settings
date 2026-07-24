# Export

code --list-extensions | tee extensions.txt

# Import

## Add the extension per file list somewhere and install via xargs
cat extensions.txt | xargs -L 1 code --install-extension    // Serve content as one and split serve 1 arg per execution of the command 

# Sample Extension codes

catppuccin.catppuccin-vsc
catppuccin.catppuccin-vsc-icons
aaron-bond.better-comments
shardulm94.trailing-spaces
streetsidesoftware.code-spell-checker
eamodio.gitlens
alefragnani.project-manager
esbenp.prettier-vscode
mrmlnc.vscode-autoprefixer
dsznajder.es7-react-js-snippets
bmewburn.vscode-intelephense-client
ms-python.python
ms-python.vscode-pylance
ms-python.debugpy
ms-python.black-formatter
benjaminkott.typo3-typoscript
febley.typo3-fluid-snippets
leon-wbr.vscode-typo3-fluid
ralffreit.typo3snippets
glenn2223.live-sass
ecmel.vscode-html-css
redhat.vscode-xml
anthropic.claude-code
ms-vscode-remote.remote-containers
natizyskunk.sftp
ritwickdey.liveserver
