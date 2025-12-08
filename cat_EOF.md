w1.md
Helllo,

bash command that i learnt:

use: cat << EOF > (file) for easier file creation

EXAMPLE:

> $ cat << EOF > test.md
> This file was created using a here command, cat
>I can write multiple lines of text in the document.
>To end it, I will write EOF on the next line.
>EOF

Note: The > operator appends to the file, and it can be switched out for the >> operator, which writes to a file, overwrite the file if it already exists