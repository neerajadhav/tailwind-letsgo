# Tailwind Letsgo
A shell script to automate the tailwind installation process.

## Prerequisites
Node Js is required to run this script.
If not installed, install it using this link
https://nodejs.org/en/download/

## Run the script
```
$ source tailwind.sh
```

## The following commands will be executed

*Note: The commands are executed in order as the script is sourced. You do not have to run them manually.*

1. Install Tailwind CSS
- Install tailwindcss via npm, and create your tailwind.config.js file.
2. Configure your template paths
- Add the paths to all of your template files in your tailwind.config.js file.
3. Add the Tailwind directives to your CSS
- Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
4. Start the Tailwind CLI build process
5. Start using Tailwind in your HTML