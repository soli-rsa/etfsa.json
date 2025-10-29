# etfsa.json

A comprehensive repository for managing and analyzing ETF (Exchange-Traded Fund) and savings account data from the Johannesburg Stock Exchange (JSE), structured in machine-readable formats.

## Overview

This repository provides structured data and documentation for South African ETFs, AMETFs (Actively Managed ETFs), AMCs (Actively Managed Certificates), and savings accounts. The data is formatted in multiple machine-readable formats (JSON, YAML, NUON) to facilitate integration with financial analysis tools, portfolio tracking applications, and automated investment platforms.

## Repository Structure

```
etfsa.json/
├── README.md           # This file
├── data/              # Structured data files
│   ├── etfsa.json     # Main dataset in JSON format
│   ├── etfsa.yaml     # Main dataset in YAML format
│   └── etfsa.nuon     # Main dataset in Nushell Object Notation
└── docs/              # Documentation and analysis
    ├── IDEAS.md       # Application ideas and use cases
    ├── ANALYSIS.md    # Comprehensive market analysis of JSE ETFs
    └── MEMORANDUM.md  # Analysis of actively managed products (AMETFs & AMCs)
```

## Data Structure

The dataset includes the following information for each fund:

- **Fund Name**: Official name of the ETF/fund
- **Ticker**: JSE trading symbol
- **Type**: Classification (ETF, AMETF, AMC, ETN, etc.)
- **Category**: Investment category and strategy
- **Description**: Detailed investment focus and methodology
- **Dividends Paid**: Distribution frequency (Q=Quarterly, Bi-A=Bi-Annually, M=Monthly, etc.)

### Categories Covered

#### Domestic (South African) ETFs
- Broad Equity Market Access (Top 40, All Share, Next 40)
- JSE Sector-Specific Exposure (Financials, Industrials, Resources, MidCap)
- Fixed Income and Interest Rate
- Property and REITs
- Factor-Based and Smart Beta
- Thematic and ESG

#### Foreign ETFs
- Global Equity Indices
- Regional Exposure (US, Europe, Asia, Emerging Markets)
- Sector-Specific (Technology, Healthcare, etc.)
- Fixed Income
- Commodities and Currency

#### Actively Managed Products
- Actively Managed ETFs (AMETFs)
- Actively Managed Certificates (AMCs)
- Multi-asset and balanced funds

## Documentation

### [ANALYSIS.md](docs/ANALYSIS.md)
A comprehensive market analysis providing:
- Comparative overview of domestic vs. foreign ETFs
- Detailed categorization of investment options
- Analysis of weighting methodologies (market-cap vs. SWIX)
- Sector-specific and thematic investment strategies
- Current market data as of October 2025

### [MEMORANDUM.md](docs/MEMORANDUM.md)
An investment committee memorandum analyzing:
- Actively Managed ETFs (AMETFs) landscape
- Actively Managed Certificates (AMCs)
- Strategic allocation opportunities
- Geographic and asset class diversification strategies

### [IDEAS.md](docs/IDEAS.md)
A categorized list of potential applications and use cases, including:
- Portfolio tracking and analytics tools
- Risk assessment applications
- Fee comparison utilities
- API services and data integration
- Educational and visualization tools

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/soli-rsa/etfsa.json.git
   cd etfsa.json
   ```

2. **Explore the data:**
   - View data files in the `data/` directory
   - Choose your preferred format: JSON, YAML, or NUON

3. **Read the documentation:**
   - Start with [ANALYSIS.md](docs/ANALYSIS.md) for market insights
   - Review [IDEAS.md](docs/IDEAS.md) for application inspiration
   - Check [MEMORANDUM.md](docs/MEMORANDUM.md) for active management strategies

## Use Cases

This dataset can be used for:

- **Financial Analysis**: Analyze trends, correlations, and performance metrics
- **Portfolio Construction**: Build diversified investment portfolios
- **API Development**: Create REST APIs for querying ETF/SA data
- **Investment Tools**: Develop screeners, comparators, and trackers
- **Educational Platforms**: Build learning tools for investors
- **Tax Reporting**: Generate reports for tax filing purposes
- **Risk Management**: Assess portfolio risk and exposure

## Data Formats

### JSON
Standard JSON format for maximum compatibility with modern applications and APIs.

### YAML
Human-readable YAML format, ideal for configuration management and data visualization tools.

### NUON (Nushell Object Notation)
Optimized for use with [Nushell](https://www.nushell.sh/), a modern shell with built-in data manipulation capabilities.

## Contributing

Contributions are welcome! Here's how you can help:

- **Data Updates**: Submit corrections or additions to fund data
- **Documentation**: Improve analysis or add new insights
- **App Ideas**: Suggest new use cases in [IDEAS.md](docs/IDEAS.md)
- **Bug Reports**: Report data inconsistencies or errors

Please open an issue or submit a pull request with your contributions.

## Data Currency

The data in this repository is current as of **October 2025**. For the most up-to-date information, please verify directly with the JSE or fund providers.

## Disclaimer

This repository is for informational and educational purposes only. It does not constitute financial advice. Always consult with a qualified financial advisor before making investment decisions. The maintainers of this repository are not responsible for any investment decisions made based on this data.

## License

[Specify your license here, e.g., MIT, Apache 2.0, etc.]

## Resources

- [Johannesburg Stock Exchange (JSE)](https://www.jse.co.za)
- [Application Ideas](docs/IDEAS.md)
- [Market Analysis](docs/ANALYSIS.md)
- [Active Management Analysis](docs/MEMORANDUM.md)

---

**Questions or suggestions?** Open an issue or contribute to the discussion!