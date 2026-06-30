PDF Grid Label Generator

This application is a specialized tool designed for automated, grid-based PDF label generation. It allows users to convert raw contact information from Excel files into a precisely formatted A4 document layout, perfect for mailing labels, visitor badges, or inventory tags.

Purpose

This tool solves the challenge of maintaining strict document geometry when printing labels. It ensures that data extracted from your spreadsheet is placed into a "locked" grid layout (2 columns × 8 rows), preventing text overflow, layout drift, or misalignment.

Key Features

Locked Grid Layout: Adheres to a strict 2 x 8 (16 boxes per page) grid on an A4 sheet.

Mathematical Precision: Each box is calculated with exact dimensions based on your page margins, ensuring consistent output regardless of the number of pages.

Dynamic Mapping: Easily map your Excel columns to the Firm Name, Address, and Phone Number fields used in the PDF.

Live Preview: Visualize exactly how the first page will render before committing to a full PDF generation.

Error-Free Generation: Built-in safeguards ensure that data is cleanly truncated or wrapped, maintaining the integrity of the grid and preventing overlapping content.

How to Use

Upload: Select your Excel (.xlsx or .xls) file containing your contact data.

Map Columns: Use the dropdown selectors to indicate which columns in your spreadsheet correspond to the Firm Name, Address, and Phone Number.

Verify: Check the Live Preview to ensure your data is mapping correctly to the boxes.

Generate: Click the "Generate & Download PDF" button to download your document as a high-resolution PDF file.

Technical Specifications

Page Size: A4 (210mm x 297mm)

Margins: 5mm on all sides.

Grid Layout: 2 Columns, 8 Rows (16 boxes/page).

Box Dimensions: 100mm x 35.875mm.

Technology: Built with jsPDF for PDF rendering, SheetJS for Excel parsing, and Tailwind CSS for the interface.
