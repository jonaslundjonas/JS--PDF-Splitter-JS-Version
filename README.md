# JS--PDF-Splitter-JS-Version
PDF Splitter HTML/JS version
  PDF Splitter Web Interface
    Written by Jonas Lund 2024

    Description:
    This web application splits a PDF file into multiple smaller PDF files of approximately equal size.
    The application runs entirely in the browser using client-side JavaScript, so no server is needed.
    
    Requirements:
    - A modern web browser
    - JavaScript enabled
    - pdf-lib library (automatically loaded from CDN)
    
    How to use:
    1. Open this HTML file in a web browser
    2. Click "Select PDF file" to choose your PDF
    3. Enter the number of pieces you want to split the PDF into
    4. Click "Split PDF"
    5. Each part will automatically download to your computer
    
    Output:
    - Creates separate PDF files named part_1.pdf, part_2.pdf, etc.
    - Original file remains unchanged
    - Each part contains an approximately equal number of pages
    
    Note: Large PDF files may take longer to process since all processing happens in the browser.
    
