# Wammu

Copies a file to a destination directory, ensuring there is enough space for
the copy by deleting oldest files.

## THE BIG RED WARNING

THIS PROGRAM DOES HAVE CODE TO DELETE FILES TO ENSURE THERE'S ENOUGH SPACE FOR
THE COPY. THERE IS A CHANCE AN IMPORTANT FILE IN THE DESTINATION DIRECTORY WILL
BE DELETED. DO NOT RUN THIS PROGRAM IF THE DESTINATION DIRECTORY CONTAINS
IMPORTANT FILES. YOU HAVE BEEN WARNED.

## Usage

    wammu <source-file> <dest-dir|dest-file>

