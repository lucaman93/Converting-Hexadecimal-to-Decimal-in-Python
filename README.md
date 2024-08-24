# Converting-Hexadecimal-to-Decimal-in-Python
# Hexadecimal values given
n_hex = "..."  # Replace with actual hexadecimal value
c_hex = "..."  # Replace with actual hexadecimal value
e_hex = "..."  # Typically, this is just 65537 in decimal

# Convert hexadecimal to decimal
n_decimal = int(n_hex, 16)
c_decimal = int(c_hex, 16)
e_decimal = int(e_hex, 16)

print("Decimal n:", n_decimal)
print("Decimal c:", c_decimal)
print("Decimal e:", e_decimal)

This is a common task when working with cryptographic data, where hexadecimal values are often used to represent large numbers. 
 Hexadecimal to Decimal Conversion:

The hexadecimal (base 16) number system is commonly used in computing. It's important to be able to convert hexadecimal values into decimal (base 10) format for various applications, especially in fields like cryptography.
int() Function:

The int() function in Python can be used to convert a string representation of a number in a specified base (in this case, 16 for hexadecimal) to its decimal form.
Variables n_hex, c_hex, e_hex:

These variables hold hexadecimal values that you need to convert to decimal. In cryptographic contexts, these variables often represent important numbers like the modulus (n), ciphertext (c), and exponent (e).
Print Statements:

The print() function is used to display the converted decimal values, helping you verify the correctness of the conversion.

