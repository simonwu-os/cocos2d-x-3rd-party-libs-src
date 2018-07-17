
1) clang dont support -mandroid cflag.
so we should remove it.
refer to: 
https://stackoverflow.com/questions/42635999/android-studio-clang-error-unknown-argument-mandroid

create diff patch

diff -u original.c new.c > original.patch

or use git to create diff patch.

2) generate sha512 

shasum -a 512 -b <file_path>

