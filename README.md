# Invoice Generator

This project is an Invoice Generator built using React and Tailwind CSS. It allows users to add items with quantities, prices, tax rates, and discounts. Generated invoices can be downloaded as PDF files to your device for easy printing.

## Project Overview

### Setup and Environment
1. Initialize a new React project (`create-react-app` or similar).
2. Install necessary dependencies: Tailwind CSS, Headless UI, Html-to-image, and jsPDF.

### Designing the Invoice UI
1. Create a modal or form where users can input invoice details such as items, quantities, prices, tax rates, and discounts.
2. Use Tailwind CSS for responsive and styled components like buttons, inputs, tables, and modal dialogs.

### Capturing Invoice as Image
1. Utilize Html-to-image to capture the invoice modal/form contents as an image.
2. Convert the captured image to a canvas to prepare for PDF conversion.

### Generating PDFs with jsPDF
1. Use jsPDF to create a PDF document.
2. Incorporate captured data from the canvas (invoice details) into the PDF document.
3. Customize the layout, fonts, and styles of the PDF to resemble a professional invoice.

### Downloading and Printing Invoices
1. Implement functionality to allow users to download the generated PDF invoice.
2. Include options for users to print the invoice directly from the browser.

## Tools
- React
- Tailwind CSS
- Headless UI
- Html-to-image
- jsPDF
