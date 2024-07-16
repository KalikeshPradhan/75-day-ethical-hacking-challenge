# Linux Fundamentals

## Interacting with the Filesystem

### Navigating Directories
```bash
# Change directory
cd /path/to/directory

# List files in the current directory
ls

# List all files, including hidden files
ls -a

# List files with detailed information
ls -l

# Create a new directory
mkdir new_directory

# Remove an empty directory
rmdir empty_directory

# Remove a directory and its contents
rm -r directory

# Copy a file
cp source_file destination_file

# Move or rename a file
mv source_file destination_file

# Delete a file
rm file_to_delete
# Display the contents of a file
cat file

# Display the contents of a file one page at a time
less file

# Display the first 10 lines of a file
head file

# Display the last 10 lines of a file
tail file

# Follow the updates to a file in real-time
tail -f file

# Find files by name
find /path/to/search -name "filename"

# Find files by type
find /path/to/search -type f

# Find directories by type
find /path/to/search -type d

# Find files by size
find /path/to/search -size +100M

# Execute a command on each found file
find /path/to/search -name "filename" -exec command {} \;


# Search for a pattern in a file
grep "pattern" file

# Search for a pattern in multiple files
grep "pattern" file1 file2 file3

# Search for a pattern recursively in a directory
grep -r "pattern" /path/to/search

# Display line numbers with matching lines
grep -n "pattern" file

# Perform a case-insensitive search
grep -i "pattern" file

# Display only the filenames with matching lines
grep -l "pattern" *


Operators
Background Execution: &
bash
Copy code
# Run a command in the background
command &
Logical AND: &&
bash
Copy code
# Run the second command only if the first command succeeds
command1 && command2
Redirecting Output: >
bash
Copy code
# Redirect the output of a command to a file, overwriting the file if it exists
command > file
Appending Output: >>
bash
Copy code
# Redirect the output of a command to a file, appending to the file if it exists
command >> file
vbnet
Copy code

You can copy and paste this Markdown code into your GitHub repository to document these Linux funda
