# Project 2
Repository for "C2 Problem Based Learning", EL4203-1 Advanced Programming (Fall/Autumn 2024)

The main functions are:

1. format_text(text: str, max_width: int) -> List[str]: This function formats a given text so that each line has a maximum width of max_width characters. The lines are justified, except for the last one. It also handles multiple spaces between words.
2. justify_line(line: List[str], max_width: int) -> str: This function justifies a line of words so that it has exactly max_width characters.
3. longest_common_substring(s1: str, s2: str) -> str: This function finds the longest common substring between two strings.

The script also includes a constant max_width which is set to 20. This value can be changed for testing purposes.

Installation
To run this script, you need to have Python installed on your machine. You also need to install the nose-parameterized package. You can install it using pip:
pip install nose-parameterized

Usage
You can import the functions from this script into your own Python scripts and use them as follows:

from script_name import format_text, justify_line, longest_common_substring

# Example usage
formatted_text = format_text("Your text here", 20)
justified_line = justify_line(["Your", "line", "here"], 20)
common_substring = longest_common_substring("Your first string here", "Your second string here")

The main functions are:

    format_text(text: str, max_width: int) -> List[str]: This function formats a given text so that each line has a maximum width of max_width characters. The lines are justified, except for the last one. It also handles multiple spaces between words.
    justify_line(line: List[str], max_width: int) -> str: This function justifies a line of words so that it has exactly max_width characters.
    longest_common_substring(s1: str, s2: str) -> str: This function finds the longest common substring between two strings.

The script also includes a constant MAX_WIDTH which is set to 20. This value can be changed for testing purposes.
Installation
To run this script, you need to have Python installed on your machine. You also need to install the nose-parameterized package. You can install it using pip:
javascript

pip install nose-parameterized

Usage
You can import the functions from this script into your own Python scripts and use them as follows:
python

from script_name import format_text, justify_line, longest_common_substring

# Example usage
formatted_text = format_text("Your text here", 20)
justified_line = justify_line(["Your", "line", "here"], 20)
common_substring = longest_common_substring("Your first string here", "Your second string here")

Replace "script_name" with the name of this script.
Testing
The script includes a unittest block for testing the functions. To run the tests, simply run the script in Python.
Contributing
Contributions are welcome. Please open an issue or submit a pull request.
