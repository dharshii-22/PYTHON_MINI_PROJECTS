## QR Code Generator 🎯📲

This Python program generates a QR code for a given input text using the `pyqrcode` library. The generated QR code is saved as a PNG image file.

### Libraries Used
- **pyqrcode** 📲: Generates QR codes.
- **pypng** 🖼️: Provides functionality to save the QR code as a PNG image.
- **tkinter** 🖼️: Used for creating the GUI.

### Functions and Methods
- **get_code()** 🔄: Takes input text, converts it to a QR code image, and saves it as a PNG file.
- **Base Window** 🖼️: Creates a Tkinter window for the QR code generator with an input field and a button to generate the QR code.
- **data** 💬: Variable to store the input text for the QR code.

### How to Use
1. Run the program.
2. Enter the text for which you want to generate a QR code.
3. Click the "Get Code" button to generate the QR code.
4. The generated QR code will be saved as `code.png` in the same directory.

### Note 📝
- Ensure you have the `pyqrcode` and `pypng` libraries installed (`pip install pyqrcode pypng`).
- The size of the QR code image can be adjusted using the `scale` parameter in the `qr.png` method.
### Sample Output 
![image](https://github.com/dharshii-22/PYTHON_MINI_PROJECTS/assets/110839215/a8546638-7be5-4fc7-a0cd-4dcc5a8331c2)


![image](https://github.com/dharshii-22/PYTHON_MINI_PROJECTS/assets/110839215/24f85f40-1fb5-4a35-a126-e1592be87224)
