# Barcode Generator

This is a simple Python script that generates a barcode using the `barcode` library. The generated barcode is in the EAN-13 format and is saved as an image file.

## Prerequisites

- Python (version 3.5 or above)
- `barcode` library

## Installation

1. Clone the repository or download the script directly.
2. Install the required dependencies by running the following command:

   ```
   pip install python-barcode
   ```

## Usage

1. Open a terminal or command prompt.
2. Navigate to the directory where the script is located.
3. Run the script using the following command:

   ```
   python barcode_generator.py
   ```

4. The script will generate an EAN-13 barcode using the value "123456789011" and save it as an image file named "my_ean13_barcode.png" in the same directory.

## Customization

- You can modify the barcode value by changing the parameter `u'123456789011'` in the `testEan()` function.
- The output image file name can be changed by modifying the parameter passed to the `save()` method in the `testEan()` function.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use it according to your needs.
