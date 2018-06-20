### Version 0.0.2
Using the tilde in the paths had some problems during linking:

~/.vscode/extensions/atomclip.darwin-arm-none-eabi-0.0.1/bin
~/.vscode/extensions/atomclip.darwin-arm-none-eabi-0.0.1/arm-none-eabi/include
~/.vscode/extensions/atomclip.darwin-arm-none-eabi-0.0.1/lib

Changed default paths:

${env:HOME}/.vscode/extensions/atomclip.darwin-arm-none-eabi-0.0.2/bin
${env:HOME}/.vscode/extensions/atomclip.darwin-arm-none-eabi-0.0.2/arm-none-eabi/include
${env:HOME}/.vscode/extensions/atomclip.darwin-arm-none-eabi-0.0.2/lib

Added GNU Make 3.81 to bin directory.