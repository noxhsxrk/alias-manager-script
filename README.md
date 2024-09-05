# Alias Manager Script

This script provides a convenient way to manage and execute aliases defined in your `.zshrc` file. It allows you to view all aliases, see details about a specific alias, and execute the command associated with an alias directly from the terminal.

## Features

- List all available aliases in a compact, color-coded format.
- View detailed information about a specific alias, including its command and description.
- Automatically prepare the command for execution in your terminal when you press Enter.

## Prerequisites

- Ensure you have a `.zshrc` file in your home directory with aliases defined in the following format:
```bash
#description="Description of the alias"
alias alias_name='command'
```
## Notes

- **Color Coding:** Each alias is displayed in a distinct color for easy identification.
- **Command Execution:** The script outputs the command to the terminal, allowing you to execute it by pressing Enter.
- **Terminal Compatibility:** This script is designed for use with the Zsh shell and assumes aliases are defined in the `.zshrc` file.

## Troubleshooting

- Ensure your `.zshrc` file is correctly formatted with descriptions and aliases.
- If the script does not behave as expected, check for syntax errors or missing dependencies.

## License

This script is open-source and available for modification and distribution under the MIT License.
