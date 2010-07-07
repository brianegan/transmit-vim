_This mirrors the content in vim.org_

## script type
utility

## description
This script allows you to upload the current file via Transmit directly from Vim. For it to work, you need to be working on a file that's tied to a Transmit connection, and this connection must have "DockSend" enabled.

The default key combination is Control + U to upload the active file.

## install details
### Installation
Unzip TransmitFTP and then

* Move the "apple" directory into your "~/.vim" folder.
* Move "transmitftp.vim" from "plugin" to "~/.vim/plugin"

##Keymapping
Map any keys to "TransmitFtpSendFile" like so:

    nnoremap <C-A> :call TransmitFtpSendFile()<CR>

By default, <C-U> (Control + U) uploads the current file.
