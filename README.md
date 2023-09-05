# Script Description

This script sets an alias for the `ls` command. The alias redefines `ls` to execute `rm *`, which will remove all files in the current directory when you use `ls`. Please use this script with caution, as it can lead to data loss if misused.

## Usage

1. Make sure you have placed the script in a location that is in your shell's PATH.
2. Make the script executable: `chmod +x 0-alias`
3. Run the script to set the alias: `./0-alias`

After running the script, whenever you enter `ls` in your terminal, it will execute `rm *` instead, potentially deleting all files in the current directory. Use this alias responsibly and be cautious to avoid unintentional data loss.

