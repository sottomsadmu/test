
# Workflow Notes
https://vim.fandom.com/wiki/Using_marks
It would be cool to incorporate marks into our workflow
mV for the VIMRC file
mI for the Index
mS for the Scratchpad/Inbox

underscore in filename is an issue where the filename underscore prompts sytax highilighting to bold characters after the underscore. It's either we escape that, then gf won't work or just don't use underscores in filenames.

coc autocomplete for filenames

http://vim.wikia.com/wiki/Open_file_under_cursor
`gf` to jump to the filename under the cursor.
`gx` open links
    it has an issue with filenames with spaces. 
    gf at the beginning of the line. 
    Make sure there are no trailing spaces
    `set isfname+=32` in vimrc


