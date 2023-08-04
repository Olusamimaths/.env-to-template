# .env to Template Converter

Description:
This bash script simplifies the process of converting a .env file to a template file. The script reads through the input .env file, replacing all values with empty strings while preserving the keys. This conversion allows developers to create reusable configuration templates that can be shared with others or used as a starting point for new projects.

## How to Use:
- Save the script in a file, e.g., convert_env_to_template.sh.
- Make the script executable using the command: chmod +x convert_env_to_template.sh.
- Run the script by providing the target .env file as a command-line argument, like this: ./convert_env_to_template.sh your_env_file.env.
- The script will generate a new file named your_env_file.env.template, containing the template version of the input .env file.
  
Use this script to streamline your configuration file management and enhance collaboration on your projects. Happy coding! 🚀
