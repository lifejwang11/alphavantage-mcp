# AlphaVantage MCP Server

[![smithery badge](https://smithery.ai/badge/@lifejwang11/alphavantage-mcp)](https://smithery.ai/server/@lifejwang11/alphavantage-mcp)

This is a server based on the MCP (Model Control Protocol) framework, designed to integrate with the AlphaVantage financial data API service.The more information about AlphaVantage is [here](https://www.alphavantage.co/documentation)

## Project Overview

AlphaVantage is an API service that provides real-time and historical financial market data, including:

- Stock market data
- Forex data
- Cryptocurrency data
- Technical indicators
- Fundamental data

This project encapsulates AlphaVantage's functionality into an MCP service, making it easier to integrate with other applications.

## MCP Server Installation

### Installing via Smithery

To install AlphaVantage MCP Server for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@lifejwang11/alphavantage-mcp):

```bash
npx -y @smithery/cli install @lifejwang11/alphavantage-mcp
```

### Prerequisites

- Python 3.12
- pip package manager

### Installation Steps

1. Clone the project

```bash
git clone https://github.com/lifejwang11/alphavantage-mcp
cd alphavantage-mcp
```

2. Create and activate virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # Unix/macOS
# or
.\venv\Scripts\activate  # Windows
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Configure environment variables

```bash
export ALPHAVANTAGE_API_KEY=your_api_key
```

5. Start the server

```bash
python main.py
```

## AlphaVantage Features

This MCP server supports the following core AlphaVantage functionalities:

1. Stock Market Data

   - Real-time quotes
   - Historical price data
   - Company information

2. Technical Indicators

   - Moving averages
   - RSI
   - MACD and more

3. Fundamental Data
   - Financial statements
   - Earnings reports
   - Company overview

## Usage Guide

1. Get AlphaVantage API Key

   - Visit [AlphaVantage website](https://www.alphavantage.co/)
   - Register and obtain API key

2. Configure API Key

   - Set ALPHAVANTAGE_API_KEY in environment variables
   - Or configure in the configuration file

3. Service Calls
   - Make calls through the MCP protocol
   - Refer to API documentation for detailed interface specifications

## Important Notes

- Please refer to AlphaVantage's official documentation for API rate limits
- Premium API keys are recommended for production environments to get higher rate limits
- Handle API keys securely and never expose them in public code

## Contributing

Issues and Pull Requests are welcome to help improve the project.

## License

MIT License

Copyright (c) 2025 lifejwang11

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
