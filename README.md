# Variables-Type-casting
integer_var = 25
float_var = 36.78
string_var = "78"

print("Values and their types:")
print(f"integer_var: {integer_var}, Type: {type(integer_var)}")
print(f"float_var: {float_var}, Type: {type(float_var)}")
print(f"string_var: '{string_var}', Type: {type(string_var)}")

converted_int = int(string_var)
print("\nConverting string to integer:")
print(f"Converted value: {converted_int}, Type: {type(converted_int)}")

converted_float_to_int = int(float_var)
print("\nConverting float to integer:")
print(f"Converted value: {converted_float_to_int}, Type: {type(converted_float_to_int)}")
