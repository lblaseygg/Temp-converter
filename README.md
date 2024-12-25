# Temperature Converter

This is a simple **Temperature Converter** program written in Python. It allows the user to convert a given temperature from Celsius to Fahrenheit or from Fahrenheit to Celsius.

---

## Features

- **Celsius to Fahrenheit Conversion**:
  - Input a temperature in Celsius to get its Fahrenheit equivalent.
- **Fahrenheit to Celsius Conversion**:
  - Input a temperature in Fahrenheit to get its Celsius equivalent.
- User-friendly input prompts and clear output.
- Handles invalid unit inputs.

---

## How It Works

1. **Input**:
   - The user is asked whether the temperature is in Celsius or Fahrenheit (using "C" or "F").
   - The user then enters the numeric temperature value.

2. **Conversion Logic**:
   - If the input is in Celsius:
     - The formula `(9 * temp) / 5 + 32` is used to convert to Fahrenheit.
   - If the input is in Fahrenheit:
     - The formula `(temp - 32) * 5 / 9` is used to convert to Celsius.

3. **Output**:
   - The result is displayed with one decimal place, followed by the corresponding unit.

4. **Error Handling**:
   - If an invalid unit is provided, an error message is displayed.

---

## Example Usage

### Input (Celsius to Fahrenheit):
```
Is this temperature in Celsius or Fahrenheit? (C or F): C
Enter the temperature: 100
```

### Output:
```
The temperature in Fahrenheit is 212.0 F
```

### Input (Fahrenheit to Celsius):
```
Is this temperature in Celsius or Fahrenheit? (C or F): F
Enter the temperature: 32
```

### Output:
```
The temperature in Celsius is 0.0 C
```

### Invalid Input Example:
```
Is this temperature in Celsius or Fahrenheit? (C or F): X
```

### Output:
```
X is not a valid unit of measurement
```

---

## File

`temp_converter.py`

This file contains the code for the Temperature Converter.

---

## Future Enhancements

- Add support for additional temperature units (e.g., Kelvin).
- Create a GUI for better user interaction.
- Add error handling for invalid numeric input.

---

## Author

Created by Luis Feliciano for practicing Python basics and simple user input handling.

