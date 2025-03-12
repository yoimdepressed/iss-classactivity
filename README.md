# iss-classactivity
Fixed function definitions:

Added colons (:) at the end of def is_narc(n) and def print_narc_numbers(start, end).

Fixed assignment errors:

Changed num_str == str(n) to num_str = str(n).

Changed num_digits == len(num_str) to num_digits = len(num_str).

Fixed exponentiation:

Changed sum(int(digit) * num_digits for digit in num_str) to sum(int(digit) ** num_digits for digit in num_str).

Fixed function name mismatch:

Renamed print_narcis_numbers to print_narc_numbers to match the function call at the end.

Fixed function call:

Changed if is_narcissistic(num) to if is_narc(num).

Fixed missing colons:

Added colons (:) at the end of for num in range(start, end + 1) and if is_narc(num).

Fixed docstring:

Updated the docstring for is_narc to clarify that it checks for narcissistic numbers.
