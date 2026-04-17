# a-power-electronics-teaching-platform

## Prerequisites

To compile this book, you need to have **Quarto** installed on your system. 

1.  **Install Quarto:** [Download here](https://quarto.org/docs/get-started/)
2.  **TinyTeX (Recommended):** Required if you want to generate PDF output.
    ```bash
    quarto install tinytex
    ```

## How to Compile

You can render the book using the Quarto CLI. Open your terminal in the project root directory and run one of the following:

### Render All Formats
This will generate all formats specified in the `_quarto.yml` file:
```bash
quarto render
