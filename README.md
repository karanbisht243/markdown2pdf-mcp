# markdown2pdf-mcp 🚀

Welcome to the **markdown2pdf-mcp** repository! This project serves as a client for the markdown2pdf.ai service, designed to facilitate seamless conversion from Markdown to PDF. Agents communicate in Markdown, while humans often prefer the polished format of PDF. This tool bridges that gap, enhancing your agentic workflow.

![Markdown to PDF](https://img.shields.io/badge/Markdown%20to%20PDF-Conversion-blue)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)
- [Support](#support)

## Introduction

In today's digital landscape, Markdown has become a standard format for documentation and communication. However, when it comes to sharing that information with a broader audience, PDF remains the preferred choice. The **markdown2pdf-mcp** client allows you to convert your Markdown files into high-quality PDF documents effortlessly.

Whether you're an agent working with Markdown or a developer looking to enhance your workflow, this tool simplifies the process. You can focus on creating content while we handle the conversion.

## Features

- **Simple Conversion**: Convert Markdown files to PDF with a single command.
- **No Sign-ups Required**: Start using the service immediately without the hassle of creating accounts or entering credit card information.
- **Bitcoin Payment**: Use Bitcoin for transactions, making it easy to pay for conversions.
- **Lightning Network Support**: Quick and efficient payments through the Lightning Network.
- **User-Friendly Interface**: Designed with simplicity in mind, making it accessible for all users.
- **Agent-Friendly**: Tailored for agents who prefer Markdown, ensuring a smooth workflow.

## Installation

To get started with **markdown2pdf-mcp**, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/karanbisht243/markdown2pdf-mcp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd markdown2pdf-mcp
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```

## Usage

After installation, you can start converting Markdown files to PDF. Here’s how:

1. Prepare your Markdown file. For example, create a file named `example.md` with your content.
2. Use the following command to convert it to PDF:
   ```bash
   node convert.js example.md
   ```
3. The output PDF will be saved in the same directory.

For more detailed usage instructions, refer to the [API Reference](#api-reference).

## API Reference

### Convert Markdown to PDF

**Endpoint**: `/convert`

**Method**: `POST`

**Request Body**:
```json
{
  "markdown": "Your Markdown content here"
}
```

**Response**:
- **200 OK**: Returns the PDF file.
- **400 Bad Request**: If the Markdown content is invalid.

### Example Request

```bash
curl -X POST http://localhost:3000/convert -H "Content-Type: application/json" -d '{"markdown": "# Hello World"}'
```

### Example Response

```json
{
  "pdfUrl": "http://localhost:3000/download/example.pdf"
}
```

## Contributing

We welcome contributions to improve **markdown2pdf-mcp**. If you have ideas, bug fixes, or new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix:
   ```bash
   git checkout -b feature/my-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add my feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/my-feature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

To download the latest version of the **markdown2pdf-mcp** client, visit the [Releases](https://github.com/karanbisht243/markdown2pdf-mcp/releases) section. Make sure to download the appropriate file for your system and execute it to get started.

## Support

If you encounter any issues or have questions, feel free to open an issue in the repository. We are here to help!

## Topics

This project covers a variety of topics relevant to modern development and payment systems:

- **Agent**: A software agent that interacts with users.
- **Agentic AI**: AI that empowers users through agent-like functionalities.
- **Bitcoin**: A decentralized digital currency used for transactions.
- **Lightning Network**: A second layer on the Bitcoin blockchain for faster transactions.
- **Markdown**: A lightweight markup language for formatting text.
- **PDF Generation**: The process of creating PDF documents from various formats.

## Conclusion

The **markdown2pdf-mcp** client is designed to streamline the process of converting Markdown to PDF. With its user-friendly approach and support for Bitcoin payments, it fits perfectly into the modern workflow of agents and developers alike. 

Explore the [Releases](https://github.com/karanbisht243/markdown2pdf-mcp/releases) to get the latest version and enhance your productivity today!