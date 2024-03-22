# Digital Resume QR Code Generator

This Node.js project generates a QR code for a given URL, allowing users to create a digital resume QR code image. The generated QR code image can be used to quickly share a link to the user's resume or portfolio.

## Features

- **QR Code Generation**: The program generates a QR code image from a user-provided URL using the `qr-image` library.
- **User Input**: Users are prompted to enter the URL they want to encode into the QR code (add resume URL).
- **File Output**: The generated QR code image is saved as a PNG file (`url_qr_img.png`) in the project directory.
- **URL Logging**: The input URL is also saved in a text file (`URL.txt`) for reference.

## How to Use

1. Install Node.js on your system if you haven't already.
2. Install the required dependencies by running `npm install` in the project directory.
3. Run the JavaScript file (`index.js`) using Node.js to start the program.
4. Follow the prompts to enter the URL you want to encode into the QR code.
5. Once the QR code is generated, you can find the PNG image file (`url_qr_img.png`) and the text file containing the URL (`URL.txt`) in the project directory.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): Used to prompt users for input in the command line interface.
- [qr-image](https://www.npmjs.com/package/qr-image): Library for generating QR codes.

## Contributing

Contributions to the Digital Resume QR Code Generator project are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for personal or commercial purposes.

## Acknowledgments

- Inspired by the convenience of QR codes for sharing digital content, this project aims to provide a simple tool for generating QR codes for resumes or portfolios.
- Thanks to the Node.js community for providing libraries and tools to facilitate command line interface applications.

## Contact

For any questions or inquiries about the Digital Resume QR Code Generator project, feel free to contact vinuri.rodrigo@gmail.com. Enjoy sharing your resume with QR codes!
