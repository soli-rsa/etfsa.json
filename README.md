# invest

## ETFSA LIST
This application watchlist is compiled by extracting and structuring all product data from the provided document's OCR text.

The final JSON output is split into four lists: `etfs`, `ametfs`, `etns`, and `amcs`.

```json
{
  "etfs": [
    {
      "name": "1nvest Top 40 ETF",
      "ticker": "ETFT40",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Market cap Top 40 shares, same portfolio as Satrix 40 and FNB Top 40",
      "dividends_paid": "Q"
    },
    {
      "name": "1nvest SWIX Capped ETF",
      "ticker": "ETFSWX",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Shareholder weighted adjusted Top 40 shares. Same portfolio as Satrix SWIX Top 40.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X Wealth Next 40 Equal Weighted ETF",
      "ticker": "WNXT40",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Investors are able to get equal weighted exposure to the \"Next 40\" companies on the JSE (ranked 21-60). Is designed to be used in conjunction with 10X Wealth Top 20 Capped ETF.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X Wealth Top 20 Capped ETF",
      "ticker": "WTOP20",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Provides investors with exposure to large-cap companies (shares ranked 1-20) on the JSE. This portfolio is designed to be used in conjunction with 10X Next 40 Equal Weighted ETF.",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB Top 40 ETF",
      "ticker": "FNBT40",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Same portfolio as Satrix 40, but lower cost structure.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix 40 ETF",
      "ticker": "STX40",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Market cap index of JSE Top 40 blue chip shares on the JSE – high exposure to mining and large cap shares.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix SWIX Top 40 ETF",
      "ticker": "STXSWX",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Adjusts the Top 40 weighting to exclude all South African shares held by foreigners. Reduces the portfolio exposure to mining and dual listed shares.",
      "dividends_paid": "Q"
    },
    {
      "name": "Sygnia Itrix Top 40 ETF",
      "ticker": "SYGT40",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Top 40",
      "description": "Market cap index of JSE Top 40 blue chip shares on the JSE – high exposure to mining and large cap shares.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "10X S&P SA Top 50 ETF",
      "ticker": "CTOP50",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Other",
      "description": "Tracks the S&P Top 50 index of JSE shares. Includes some MidCap companies not included in Top 40 indices. Quarterly dividend.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Capped All Share ETF",
      "ticker": "STXCAP",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Other",
      "description": "Holds all 140 shares in the JSE All Share index in its portfolio, but with the exposure to any single ETF capped to 10%. This new ETF gives exposure to a number of smaller JSE companies that are not covered by any other index tracking ETF.",
      "dividends_paid": "Bi-monthly"
    },
    {
      "name": "Satrix JSE Global Equity ETF",
      "ticker": "STXJGE",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Broad Equity Market Access: Other",
      "description": "Tracks the FTSE/JSE Global Equity Index. It is based the global free float market cap which currently upweights dual-listed companies. This index consists of the top 50 companies from the FTSE/JSE All Share Index when ranked by investable market capitalisation companies.",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB MidCap ETF",
      "ticker": "FNBMID",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - JSE Sector Exposure",
      "description": "Tracks the FTSE/JSE MidCap index of 61 companies, ranked from 43 to 103 on the JSE by market capitalisation.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Capped INDI ETF",
      "ticker": "STXIND",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - JSE Sector Exposure",
      "description": "Provides access to top 25 industrial shares (manufacturing, construction, retail) on the JSE.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix FINI 15 ETF",
      "ticker": "STXFIN",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - JSE Sector Exposure",
      "description": "Exposure to local banks, insurance and financial services companies.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix RESI 10 ETF",
      "ticker": "STXRES",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - JSE Sector Exposure",
      "description": "Provides a portfolio of the top 10 mining and resource counters on the JSE.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix TRACI 3 Month ETF",
      "ticker": "STXTRA",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Floating Interest Rates",
      "description": "Provides the return of a 3 (three) month money market deposit. The interest is reinvested on a monthly basis.",
      "dividends_paid": "M"
    },
    {
      "name": "1nvest SA Bond ETF",
      "ticker": "ETFBND",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "Tracks the S&P South Africa Sovereign Bond 1+ Year Index local currency denominated Sovereign debt issued by the Government of South Africa in its domestic market with maturity of 1 year or more.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X Wealth GOVI Bond ETF",
      "ticker": "CSGOVI",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "Tracks the FTSE/JSE All Bond Government index (GOVI). Dividends/interest is accumulated and paid out quarterly.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X Yield Selected Bond ETF",
      "ticker": "CSYSB",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "Investment objective is to provide income to investors and capital growth over the long-term by tracking the price and yield performance of the South African Yield Selected Nominal Bond Index",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB Government Inflation-Linked Bond ETF",
      "ticker": "FNBINF",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "Exposure to a portfolio of SA Government Inflation Linked Fixed Interest bonds gives protection of both capital and interest against CPI inflation.",
      "dividends_paid": "M"
    },
    {
      "name": "Satrix GOVI ETF",
      "ticker": "STXGVI",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "Tracks the FTSE/JSE All Bond Government index (GOVI). Dividends/interest is accumulated and paid out quarterly.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix ILBI Bond ETF",
      "ticker": "STXILB",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "A market-value-weighted index of the performance of SA Rand denominated inflation-linked securities publicly issued by the SA Government for the domestic market.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix SA Bond Portfolio ETF",
      "ticker": "STXGOV",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Bond (fixed interest)",
      "description": "The Satrix SA Bond Portfolio participatory interests provide the investor with exposure to the S&P South Africa Sovereign Bond 1+ Year Index, which is a comprehensive, market-value-weighted index designed to track the performance of the South African Rand-denominated government bond securities publicly issued by the South African government for the domestic market.",
      "dividends_paid": "Q"
    },
    {
      "name": "1nvest SA Property ETF",
      "ticker": "ETFSAP",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Listed Property",
      "description": "Invests in the FTSE/JSE SAPY index of 22 listed property shares.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X SA Property Income ETF",
      "ticker": "CSPROP",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Listed Property",
      "description": "Tracks the SA Property Income Index (a custom index calculated independently by the S&P Dow Jones Indices). The SA Property Income Index is designed to measure the performance of large South African Listed Property Companies with an emphasis towards higher yielding companies.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix SA Property ETF",
      "ticker": "STXPRO",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Listed Property",
      "description": "A market-value-weighted index of 15 top property companies in the S&P SA Composite Property index. Individual company weights are capped at 10%.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix DIVI ETF",
      "ticker": "STXDIV",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "Selects 30 of the JSE's largest companies for their dividend payment potential over the forthcoming year. Offers high yield and potential for the rerating of share prices that pay good dividends.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Inclusion & Diversity ETF",
      "ticker": "STXID",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "This ETF will track the Refinitiv Satrix South Africa Inclusion & Diversity Index, which is a customized, comprehensive, market-value weighted index designed to track the performance of 30 JSE-listed companies that best demonstrate and promote the values of inclusion and diversity in the workplace, using key metrics that include gender, race, physical ability and background.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Low Volatility ETF",
      "ticker": "STXLVL",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "Provides an Investor with diversified exposure to 20 highly liquid constituent securities in the South African equity market that exhibit the lowest volatility as well as a low beta to the market in their performance by tracking the Absa Wits Risk-Controlled SA Low Volatility Index (\"the Low Volatility Index\"), where the constituent security's weights in the Low Volatility Index is determined by applying an equal risk contribution weighting scheme.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Momentum ETF",
      "ticker": "STXMMT",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "This is an equity-only fund which provides an investment vehicle for investors wishing to track the performance of the proprietary Satrix Momentum Index (\"benchmark index\"). A portfolio tilted towards equities which displays positive momentum characteristics and away from equities showing negative momentum characteristics.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Quality South Africa ETF",
      "ticker": "STXQUA",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "This ETF tracks the Satrix Quality Index, which includes stocks in the South African market rated by quality score, which is a composite of: return on equity; accruals ratio; and a leverage ratio.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Shari'ah Top 40 ETF",
      "ticker": "STXSHA",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "Invests in a basket of Top 40 shares using Islamic investment principals for share selection.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Value Equity ETF",
      "ticker": "STXVEQ",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Style / Smart Beta",
      "description": "Provides Investors with diversified exposure to 30 highly liquid constituents securities in the South African equity market that exhibit value characteristics (low price-to-earnings and price-to-book ratios) in their performance by tracking the Absa Wits Risk-Controlled SA Value Index (\"the Value Index\"), where the constituent security's weights in the Value Index are determined by applying an equal risk contribution weighting scheme.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix RAFI 40 ETF",
      "ticker": "STXRAF",
      "type": "ETF",
      "category": "Domestic (SA) ETFs - Fundamental Value",
      "description": "Selects 40 JSE companies using Research Affiliates Fundamental Indexation methods (RAFI), which uses fundamental accounting criteria to select \"undervalued shares\". All dividends and other income automatically reinvested (i.e., a total return fund).",
      "dividends_paid": "Q"
    },
    {
      "name": "1nvest MSCI EM Asia Index Feeder ETF",
      "ticker": "ETFEMA",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the performance of the MSCI Emerging Markets Asia Index as closely as possible. This underlying MSCI index captures large and mid-cap representation across 8 Emerging Market (EM) countries, namely China, India, Indonesia, South Korea, Malaysia, the Philippines, Taiwan, and Thailand",
      "dividends_paid": "TR"
    },
    {
      "name": "1nvest MSCI World Index Feeder ETF",
      "ticker": "ETFWLD",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the MSCI World Index using the iShares Core MSCI World UCITS ETF as a feeder fund. The MSCI World Index captures large and mid-cap representation across 23 developed markets countries. With over 1600 constituents, the Index covers approximately 85% of the free float - adjusted market capitalisation in each country.",
      "dividends_paid": "TR"
    },
    {
      "name": "1nvest S&P 500 Index Feeder ETF",
      "ticker": "ETF500",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "This ETF tracks the S&P500 index as closely as possible, in South African Rand. The fund is a feeder fund and as such it invests in the iShares Core S&P500 UCITS ETF. The S&P500 Index gives the performance of the top 500 leading US listed companies and captures approximately 80% coverage of available market capitalisation.",
      "dividends_paid": "TR"
    },
    {
      "name": "10X S&P 500 Index Feeder ETF",
      "ticker": "CSP500",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The S&P 500® index tracks 500 of the top companies in the U.S. economy. All the constituents must be U.S. companies with a market cap of USD 5.3 billion or greater. Uses Vanguard S&P 500 ETF as a feeder fund.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "10X Total World Stock Feeder ETF",
      "ticker": "GLOBAL",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the FTSE Global All Cap Index, which covers both well-established (developed) and still-developing (emerging) markets. To achieve its investment objective, the Fund will, apart from assets in liquid form consist solely of participatory interests in the Vanguard Total World Stock ETF – accordingly, the Fund is a Feeder Fund.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "FNB Global 1200 Equity Fund of Funds ETF",
      "ticker": "FNBEQF",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The FNB Global 1200 ETF provides exposure to the global equity market by tracking the S&P Global 1200. It is constructed as a composite of seven headline indices which include the S&P500 (US), S&P Europe 350, S&P TOPIX 150 (Japan), S&P/TSX 60 (Canada), S&P/ASX All Australian 50, S&P Asia 50 and S&P Latin America 40 indices.",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB MSCI Emerging Markets Feeder ETF",
      "ticker": "FNBEMG",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The MSCI Emerging Markets Investable Market Index (IMI) represents large, mid and small cap companies across 23 emerging market countries. The index covers approximately 99% of the free float-adjusted market capitalisation in each country. Uses iShares Core MSCI Emerging Markets UCITS ETF as a feeder fund",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB MSCI World ETF",
      "ticker": "FNBWDM",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The MSCI World Index represents large and mid-cap companies across 23 developed markets globally. The index covers approximately 85% of the free float-adjusted market capitalisation in each country. Uses iShares Core MSCI World UCITS ETF as a feeder fund.",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB S&P 500 Feeder ETF",
      "ticker": "FNB500",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The S&P 500® Index is widely regarded as the best single gauge of large-cap US equities. The index includes 500 leading US listed companies and captures approximately 80% coverage of available market capitalisation. Uses iShares Core S&P UCITS ETF as a feeder fund.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix ACWI (All Country World Index) ETF",
      "ticker": "STXACW",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Gives exposure directly to broadly diversified companies, combining developed and emerging markets. Maintained by Morgan Stanley Capital International (MSCI), the index comprises the stocks of nearly 3,000 companies from 23 developed countries and 24 emerging markets as of 29/12/23",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Global Balanced Fund of Funds ETF",
      "ticker": "STXGLB",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "This Fund of Funds ETF tracks a variety of global indices, reflecting different assets using underlying exchange traded funds tracking each of these asset class indices. The Index captures a risk-optimised globally diversified blend of different asset classes, calculated in ZAR.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix MSCI China Feeder ETF",
      "ticker": "STXCHN",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the MSCI China Index which captures large and mid-cap representation across China A shares, H shares, B shares, Red chips, P chips and foreign listings (e.g., ADRs). With 704 constituents, the index covers about 85% of this China equity universe.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix MSCI Emerging Markets ETF",
      "ticker": "STXEMG",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The MSCI Emerging Markets Investable Market Index (IMI) represents large, mid and small cap companies across 23 emerging market countries. The index covers approximately 99% of the free float-adjusted market capitalisation in each country. Uses iShares Core MSCI Emerging Markets UCITS ETF as a feeder fund.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix MSCI Emerging Markets ESG Enhanced ETF",
      "ticker": "STXEME",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the MSCI EM ESG Enhanced Focus Index, which is designed to maximise exposure to positive environmental, social and governance (ESG) metrics.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix MSCI India ETF",
      "ticker": "STXNDA",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the MSCI India NET TR Index, which provides broad Indian stock market exposure, designed to measure the performance of the large- and mid-cap segments of the Indian market. With 107 constituents, the index covers approximately 85% of the Indian equity universe. It is a free- float adjusted market capitalisation weighted index and is reviewed quarterly.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix MSCI World Feeder ETF",
      "ticker": "STXWDM",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The MSCI World Index represents large and mid-cap companies across 23 developed markets globally. The index covers approximately 85% of the free float-adjusted market capitalisation in each country. Uses iShares Core MSCI World UCITS ETF as a feeder fund.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix MSCI World ESG Enhanced ETF",
      "ticker": "STXESG",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the MSCI World ESG Enhanced Focus Index, which is designed to maximise exposure to positive environmental, social and governance (ESG) metrics.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix MSCI World Islamic Feeder ETF",
      "ticker": "STXWIS",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Provides the Islamic investors with exposure to the MSCI World Islamic Index and gives exposure directly to broadly diversified companies in developed markets. The Index applies stringent screens to exclude certain securities based on Shariah principles in agreement with the Shariah board appointed by the index provider.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Nasdaq 100 ETF",
      "ticker": "STXNDQ",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the Nasdaq-100 ® index; is a market cap weighted index that includes the largest 100 companies on the Nasdaq Stock Exchange. Uses iShares Nasdaq 100 UCITS ETF as a feeder fund.",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix S&P 500 Feeder ETF",
      "ticker": "STX500",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The S&P 500® Index is widely regarded as the best single gauge of large-cap US equities. The index includes 500 leading US listed companies and captures approximately 80% coverage of available market capitalisation. Uses iShares Core S&P UCITS ETF as a feeder fund.",
      "dividends_paid": "TR"
    },
    {
      "name": "Sygnia Itrix Eurostoxx 50 ETF",
      "ticker": "SYGEU",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Provides access in rands, and with no foreign exchange controls for individuals, to a portfolio of the Top 50 European shares.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix FTSE 100 ETF",
      "ticker": "SYGUK",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Provides access in rands, and with no foreign exchange controls for individuals, to a portfolio of the Top 100 companies on the London Stock Exchange.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix MSCI Emerging Markets 50 ETF",
      "ticker": "SYGEMF",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the performance of the MSCI Emerging Markets 50 (MSCI EM 50 Index) (\"benchmark index\"). It also aims to replicate the price and yield performance of the MSCI Emerging Markets 50.",
      "dividends_paid": "TR"
    },
    {
      "name": "Sygnia Itrix MSCI Japan ETF",
      "ticker": "SYGJP",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Provides access in rands, and with no foreign exchange controls for individuals, to a portfolio of the Top 400 Japanese shares.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix MSCI USA ETF",
      "ticker": "SYGUS",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Provides access in rands, and with no foreign exchange controls for individuals, to a portfolio of the Top 600 US companies.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix MSCI World ETF",
      "ticker": "SYGWD",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Provides access in rands, and with no foreign exchange controls for individuals, to a portfolio of some 1900 shares worldwide.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix S&P 500 ETF",
      "ticker": "SYG500",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Tracks the S&P 500® Index. The index includes 500 leading US listed companies and captures approximately 80% coverage of available market capitalisation.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix S&P Global 1200 ESG ETF",
      "ticker": "SYGESG",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "The objective is to provide an investment vehicle to investors who want to achieve long term capital appreciation in tracking the performance of the S&P Global 1200 ESG (S&P1200ESG). It also aims to replicate the price and yield performance of the S&P Global 1200 ESG Index as closely as possible by holding a portfolio of securities equivalent to the basket of securities that comprise the Index, and in similar weightings to the Index",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix MSCI China Feeder ETF",
      "ticker": "SYGCN",
      "type": "ETF",
      "category": "Foreign ETFs - Broad Equity Market Access",
      "description": "Its objective is to replicate the price and yield performance of the S&P New China Sectors Index. This index tracks China and Hong Kong domiciled companies in consumption and service criteria industries.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "1nvest Global Government Bond Index Feeder ETF",
      "ticker": "ETFGGB",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "Tracks the FTSE Group-of-7 (G7) Index (\"the Index\"). The fund is a feeder fund and as such it invests in the iShares Global Govt Bond UCITS ETF. The G7 Government Bond Index includes Canada, France, Germany, Italy, Japan, the United Kingdom, and the United States.",
      "dividends_paid": "Q"
    },
    {
      "name": "1nvest ICE US Treasury Short Bond Index Feeder ETF",
      "ticker": "ETFUSD",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "Tracks the capital and income performance of the ICE US Treasury Short Bond Index, which is market value weighted, and is designed to include U.S. dollar denominated, fixed rate securities (Treasury Bills and Treasury Notes) with minimum term to maturity greater than one month and less than or equal to one year",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB World Government Bond ETF",
      "ticker": "FNBWGB",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "This ETF provides investors with cost efficient exposure to the global bond market by tracking the Citi World Government Bond Index (WGBI). The WGBI is a widely used benchmark that currently comprises sovereign debt from over twenty countries, including the US, UK, Canada, Germany, Japan, Australia, France and South Africa.",
      "dividends_paid": "Q"
    },
    {
      "name": "FNB 2-year US Dollar Custodial Certificate ETF",
      "ticker": "DCCUS2",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "US Dollar Custodial Certificates (DCCs) are easily tradable, dollar-denominated ETF investment instruments which have no exchange control implications. Investors earn the return of a US Treasury note, receiving an income stream in US dollars, which is settled in rands.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "FNB 10-year US Dollar Custodial Certificate ETF",
      "ticker": "DCCUSD",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "Tracks the Bloomberg Barclays Global Aggregate Bond Index, offering investors easy access to global investment grade bonds.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Satrix Global Aggregate Bond Feeder ETF",
      "ticker": "STXGBD",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "Tracks the Bloomberg Barclays Global Aggregate Bond Index, offering investors easy access to global investment grade bonds.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Satrix S&P Namibia Bond ETF",
      "ticker": "STXNAM",
      "type": "ETF",
      "category": "Foreign ETFs - Bonds",
      "description": "The Portfolio will track and replicate the total return version of the S&P Namibia Sovereign Bond 1+ year Top 10 Index in local currency of the Republic of Namibia, an index whereby each constituent bond has a maturity of greater than or equal to 12 months.",
      "dividends_paid": "Q"
    },
    {
      "name": "1nvest Global REIT Index Feeder ETF",
      "ticker": "ETFGRE",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "Tracks the FTSE EPRA/NAREIT Global REIT Index (\"the Index\"). The fund is designed to track the performance of listed real estate companies and Real Estate Investment Trusts (REITs) worldwide. Uses iShares Global REIT ETF as a feeder fund.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X S&P Global Property ETF",
      "ticker": "GLPROP",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "Tracks the S&P Global Property 40 index. The S&P Global Property 40 index provides exposure to the 40 largest global property companies in developed markets that have earnings and dividend stability.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Reitway Global Property Diversified Prescient ETF",
      "ticker": "RWDVF",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "Managed by Reitway Global (Pty) Ltd, tracks an index of diversified global property shares.",
      "dividends_paid": "Q"
    },
    {
      "name": "Reitway Global Property ESG Prescient ETF",
      "ticker": "RWESG",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "Tracks a proprietary index of global property shares that have ESG credentials. The portfolio is managed by Reitway Global (Pty) Ltd.",
      "dividends_paid": "Q"
    },
    {
      "name": "Reitway Global Property Income Prescient ETF",
      "ticker": "RWINC",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "The Portfolio tracks the Reitway Global Property index, which focuses on high income property securities..",
      "dividends_paid": "Q"
    },
    {
      "name": "Reitway Global Property Prescient ETF",
      "ticker": "RWGPR",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "The primary objective of the ETF is to track a rule driven, market liquidity-based index, which aims to outperform traditional market cap weighted comparatives. Designed to give investors an exposure to global properties by replicating and tracking the Reitway Global Property Index..",
      "dividends_paid": "Q"
    },
    {
      "name": "Sygnia Itrix Global Property ETF",
      "ticker": "SYGP",
      "type": "ETF",
      "category": "Foreign ETFs - Listed Property",
      "description": "Tracks the S&P Global Property 40 index. The S&P Global Property 40 index provides exposure to the 40 largest global property companies in developed markets that have earnings and dividend stability.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "1nvest MSCI World Socially Responsible Investment (SRI) Index Feeder ETF",
      "ticker": "ETFSRI",
      "type": "ETF",
      "category": "Foreign ETFs - Style / Smart Beta",
      "description": "Tracks the performance of the MSCI World SRI Select Reduced Fossil Fuel Index (the Index) by investing in the iShares MSCI World SRI UCITS ETF. This index includes large and mid-cap securities across 23 Developed Market countries which adhere to specific climate change and ESG criteria.",
      "dividends_paid": "Q"
    },
    {
      "name": "1nvest S&P 500 Info Tech Index Feeder ETF",
      "ticker": "ETF5IT",
      "type": "ETF",
      "category": "Foreign ETFs - Style / Smart Beta",
      "description": "This fund tracks the S&P500 Info Tech Index which comprises those companies that are included in the S&P500 Index and classified as members of the GICS® Information Technology sector. Uses iShares S&P 500 Information Technology UCITS ETF as a feeder fund.",
      "dividends_paid": "TR"
    },
    {
      "name": "10X S&P Global Dividend Aristocrat ETF",
      "ticker": "GLODIV",
      "type": "ETF",
      "category": "Foreign ETFs - Style / Smart Beta",
      "description": "This ETF tracks the S&P Global Dividend Aristocrats Blend Index. The index is designed to simulate a portfolio of S&P regional Dividend Aristocrats underlying indices diversified across Canada, Europe, Pan Asia and the United States. The objective is to track companies that have demonstrated consistent levels of paying out dividends.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Satrix Global Infrastructure ETF",
      "ticker": "STXIFR",
      "type": "ETF",
      "category": "Foreign ETFs - Style / Smart Beta",
      "description": "Tracks the performance of international infrastructure companies from both developed and emerging countries. Constituent are selected from FTSE Global All Cap Index where at least 65% of their revenue comes from infrastructure activities.",
      "dividends_paid": "Q"
    },
    {
      "name": "Satrix Healthcare Innovation Feeder ETF",
      "ticker": "STXHLT",
      "type": "ETF",
      "category": "Foreign ETFs - Style / Smart Beta",
      "description": "Tracks the performance of the STOXX Global Breakthrough Healthcare index, which is composed of developed and emerging market companies that generate significant revenues from specific sectors focused on pushing the boundaries in medical treatment and technology",
      "dividends_paid": "TR"
    },
    {
      "name": "Satrix Smart City Infrastructure Feeder ETF",
      "ticker": "STXCTY",
      "type": "ETF",
      "category": "Foreign ETFs - Style / Smart Beta",
      "description": "Seeks to track the performance of the STOXX Global Smart City Infrastructure Index, which offers exposure to companies that benefit from the urbanisation megatrend, focusing on providing services for development and efficient running of cities in a sustainable manner",
      "dividends_paid": "TR"
    },
    {
      "name": "1nvest Gold ETF",
      "ticker": "ETFGLD",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical gold bullion. Providing direct exposure to the gold price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "1nvest Palladium ETF",
      "ticker": "ETFPLD",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical palladium bullion. Providing direct exposure to the palladium price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "1nvest Platinum ETF",
      "ticker": "ETFPLT",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical platinum bullion. Providing direct exposure to the platinum price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "1nvest Rhodium ETF",
      "ticker": "ETFRHO",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical rhodium bullion. Providing direct exposure to the rhodium price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "Absa NewGold ETF",
      "ticker": "GLD",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical gold bullion. Providing direct exposure to the gold price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "Absa NewPlat ETF",
      "ticker": "NGPLT",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical platinum bullion. Providing direct exposure to the platinum price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "Absa NewGold Palladium ETF",
      "ticker": "NGPLD",
      "type": "ETF",
      "category": "Commodities - ETFs",
      "description": "Invests in physical palladium bullion. Providing direct exposure to the palladium price, traded in rands as an \"inward investment\" on the JSE.",
      "dividends_paid": "ND"
    }
  ],
  "ametfs": [
    {
      "name": "10X Income AMETF",
      "ticker": "INCOME",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Actively managed portfolio constituted of fixed interest and inflation-linked RSA bonds, private local and offshore credit instruments, plus money market.",
      "dividends_paid": "Q"
    },
    {
      "name": "10X All Asia AMETF",
      "ticker": "APACXJ",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Actively managed portfolio of Asian markets, excluding Japan, but including Australia and New Zealand.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "27four Global Multi-Factor Equity AMETF",
      "ticker": "27FGMF",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The AMETF aims to generate medium to long-term capital growth and will seek to follow an investment policy which will provide exposure to the universe of liquid companies listed on various developed global exchanges, through a style-based multi-factor strategy.",
      "dividends_paid": "Q"
    },
    {
      "name": "27four Global Shariah Equity AMETF",
      "ticker": "27FGSE",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "This AMETF will aim to achieve capital growth with a reasonable level of income that is Shari'ah compliant (permissible) for investors through investment in the global equity market.",
      "dividends_paid": "Q"
    },
    {
      "name": "27four Large Cap Equity AMETF",
      "ticker": "27FLCE",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "27four Investment Managers (Pty) Ltd, in selecting securities for the portfolio, will seek to follow an investment policy which will provide investors with exposure to the largest, liquid companies listed on the JSE. The portfolio will predominantly be invested in the top 80 companies on the JSE in terms of market capitalisation.",
      "dividends_paid": "Q"
    },
    {
      "name": "27four SA Multi-Factor Equity AMETF",
      "ticker": "27FSMF",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The AMETF will aim to generate medium to long-term capital growth and will seek to follow an investment policy which will provide exposure to the universe of liquid companies listed on the JSE, through a style-based multi-factor strategy.",
      "dividends_paid": "Q"
    },
    {
      "name": "Arysteq Short-term Income AMETF",
      "ticker": "ASIETF",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Arysteq AMETF aims to invest in Namibian short-term income instruments with an aim to provide an investment vehicle that gives access to investors who want to achieve higher levels of income while preserving their capital and liquidity.",
      "dividends_paid": "Q"
    },
    {
      "name": "CoreSolutions - Wealth Global Equity CoreSolutions AMETF",
      "ticker": "PCWGE",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "This AMETF is issued by the \"white label\" arm of 10X Investments and gives exposure to global equity securities and is managed by CoreSolutions Fund Managers.",
      "dividends_paid": "t.b.a."
    },
    {
      "name": "Coronation Global Capital Plus Prescient Feeder AMETF",
      "ticker": "COGCAP",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The underlying fund will be actively managed and diversified and will aim to outperform the Benchmark, by investing more than 60% of its net assets in equities, deposits, fixed income and debt and debt-related instruments to take advantage of particular circumstances or where market or other factors so warrant.",
      "dividends_paid": "A"
    },
    {
      "name": "Coronation Global Emerging Markets Prescient Feeder AMETF",
      "ticker": "COGEM",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The underlying fund will be actively managed by investing its assets in equities and equity-related securities (such as warrants), convertible preference shares, and convertible bonds), of companies listed or traded on a recognized exchange in an emerging market country; and/or of holding companies which have the predominant part their business activities in an emerging market country; and/or of holdings companies that have predominant part of their assets in companies with their registered office in an emerging market country.",
      "dividends_paid": "A"
    },
    {
      "name": "Coronation Global Equity Select Prescient Feeder AMETF",
      "ticker": "COGES",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The underlying fund is actively managed to maximize long-term growth by investing, either directly or indirectly, at least 80% of the fund's assets in equities, equity-related securities, and CIS. The underlying fund may also invest up to 20% of its NAV in fixed income securities, debt securities, commodities (such as oil, gold, and iron), cash and cash equivalents.",
      "dividends_paid": "A"
    },
    {
      "name": "Coronation Global Managed Prescient Feeder AMETF",
      "ticker": "COGMAN",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The underlying fund will be actively managed to achieve long-term capital appreciation by directly investing in at least 80% of its net assets in equities, listed real estate, listed commodities, deposits, fixed income and debt and debt-related instruments to take advantage of particular circumstances or where market or other factors so warrant.",
      "dividends_paid": "A"
    },
    {
      "name": "Coronation Global Opportunities Equity Prescient Feeder AMETF",
      "ticker": "COGOE",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The objective is to give investors access to some of the best fund managers across the globe. The intent is to outperform its benchmark over any five-year period, by investing, either directly or indirectly, up to 100% of the fund's Net Asset Value in equities, equity-relative securities, and CIS products.",
      "dividends_paid": "A"
    },
    {
      "name": "Coronation Global Optimum Growth Prescient Feeder AMETF",
      "ticker": "COOPTI",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The underlying fund aims to achieve its investment objective by investing in a range of equity and equity-related securities, fixed income securities, cash and cash equivalents, collective investment schemes and instruments providing exposure to commodities and property. The underlying fund will be managed with an equity bias over time, with total exposure to equities and equity-related securities expected to average between 60% and 80% of net assets over any rolling 5-year period, with the balance invested in cash and cash equivalents, fixed income securities, collective investment schemes and instruments providing exposure to commodities and property.",
      "dividends_paid": "A"
    },
    {
      "name": "Coronation Global Strategic USD Income Prescient Feeder AMETF",
      "ticker": "COUSDI",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The objective of the underlying fund is to achieve a higher return than a US dollar short-term bank deposit. The portfolio holds debt instruments including Government and corporate bonds. It has a defensive strategy with the emphasis on providing capital and delivering consistent income.",
      "dividends_paid": "A"
    },
    {
      "name": "EasyETFs AI World AMETFF",
      "ticker": "EASYAI",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Easy Asset Management (Pty) Ltd will aim to achieve capital appreciation by following a long-term equity strategy that invests primary in foreign markets in equities that the Manager believes will benefit from the creation, adoption and utilisation of artificial intelligence.",
      "dividends_paid": "A"
    },
    {
      "name": "EasyETFs Balanced AMETFF",
      "ticker": "EASYBF",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Easy Asset Management (Pty) Ltd will aim to achieve moderate capital appreciation by following a quantitative and quantitative long-term multi-asset strategy. The portfolio will operate within the prudential asset allocation constraints and be compliant with Regulation 28 of the Pension Funds Act.",
      "dividends_paid": "t.b.a."
    },
    {
      "name": "EasyETFs Global Equity AMETFF",
      "ticker": "EASYGE",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Easy Asset Management (Pty) Ltd will aim to achieve moderate capital appreciation by following a quantitative and quantitative long-term equity strategy. The assets will consist primarily of foreign equity shares with the possibility of investments in bonds, money market instruments, securities in listed entities that are back by real estate property, participatory interest in collective investment schemes, assets in liquid form and non-equity securities.",
      "dividends_paid": "t.b.a."
    },
    {
      "name": "ETFSA Balanced Foundation Prescient AMETF",
      "ticker": "ETFSAB",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The ETFSA Prescient Balanced Foundation AMETF is designed for investors who seek a balanced approach to wealth accumulation. By blending stable income-generating assets with growth-oriented investments, it's a fairly static yet still flexible portfolio that aims to achieve sustainable long-term returns, while mitigating downside risks. It allocates funds across major asset classes, incorporating global and local indices. It maintains fully Regulation 28 compliant at al times so is ideal for retirement funds.",
      "dividends_paid": "Q"
    },
    {
      "name": "Prescient Global Income Provider Feeder AMETF",
      "ticker": "PREGIP",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The primary performance objective of the Fund is to generate real returns in US dollars and is benchmarked to the US inflation rate, converted to Rands. The underlying portfolio is in fixed interest securities denominated in US dollars.",
      "dividends_paid": "Q"
    },
    {
      "name": "Prescient PortfolioMetrix Active Income Prescient AMETE",
      "ticker": "PMXINC",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Actively managed by PortfolioMetrix Asset Management SA, this AMETF invests in South African fixed interest Government bonds and other interest bearing assets, including floating rate corporate bonds, bank, and other credit paper.",
      "dividends_paid": "Q"
    },
    {
      "name": "Prescient Numoro AQUA AMETF",
      "ticker": "AQUA",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The objective of this AMETF is to provide investors with capital growth over the medium to long term, which will employ a top-down Global Tactical Asset Allocation investment strategy designed to achieve the objective, investing in a combination of international equity, bond, money, or property markets.",
      "dividends_paid": "A"
    },
    {
      "name": "Prescient Income Provider (PIP)Feeder AMETF",
      "ticker": "PIPETF",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Invests in local and offshore money market, bonds, property, preference shares, inflation-linked bonds, and derivatives to pay a high income yield.",
      "dividends_paid": "M"
    },
    {
      "name": "RealFin Fixed Income AMETF",
      "ticker": "RFFI",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Managed by RealFin Asset Managers, this AMETF provides exposure to a variety of domestic, listed and unlisted fixed income securities, including derivatives, as allowed by the Act from time to time. The portfolio is not limited to local securities and may hold international securities in future.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Reitway Global Property Actively Managed Prescient AMETF",
      "ticker": "RWAGP",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "This Actively Managed ETF (AMETF) replicates the Reitway BCI Global Property feeder fund. It provides exposure to global real estate securities listed on recognised exchanges around the world.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix Solactive Healthcare 150 AMETF",
      "ticker": "SYGH",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Tracks the Solactive Developed Markets Healthcare 150 Price Return Index which consists of the largest 150 companies from the Developed Market Healthcare Industry, mainly the US (68%), Switzerland (9%), Japan (5%) and the UK (4%). It will follow a physical replication strategy whereby securities that substantially make up the Index are purchased at a similar weighting to the Index. The constituents are weighted based on their free float market capitalization and the portfolio will be rebalanced quarterly.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix 4th Industrial Revolution AMETF",
      "ticker": "SYG4IR",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The objective of this portfolio is to provide access to investors who wish to track the movements of the Kensho New Economies Composite Index (KNEX). This index seeks to capture the economic sectors that are propelling the “4th Industrial Revolution\".",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Sygnia Itrix FANG.AI AMETF",
      "ticker": "SYFANG",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "This AMETF provides exposure to companies that use advanced technologies to acquire and retain users, including industry disrupting technologies such as artificial intelligence, large language modes, cloud storage, big data, social media and e-commerce tools.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "TBI Global Multi-Asset Income Fund Prescient AMETF",
      "ticker": "TBIMAI",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "TBI Investment Managers Proprietary Limited aims to provide a total return from capital growth and income. The portfolio invests in fixed income, equity, currency and commodities, both through ETPs and direct securities.",
      "dividends_paid": "TR"
    },
    {
      "name": "TBI Global Targeted Yield UCITS Fund AMETF Class A",
      "ticker": "TBIGTF",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "The Fund's primary objective is to outperform short-term interest rates of developed markets to the extent consistent with the preservation of capital and maintaining liquidity. To achieve this objective, the Fund will invest in a diversified portfolio of liquid, investment grade fixed income securities with remaining maturities not longer than 1 year and floating rate notes with remaining maturities not longer than 3 years.",
      "dividends_paid": "TR"
    },
    {
      "name": "Vunani Global Equity Prescient Feeder AMETF",
      "ticker": "VUNGLE",
      "type": "AMETF",
      "category": "Actively Managed Exchange Traded Funds (AMETFs)",
      "description": "Vunani Fund Managers (Pty) Ltd will manage the underlying portfolio which will, apart from assets in liquid form, consist solely of participatory interest in the Vunani Global Equity Fund, as a Feeder Fund",
      "dividends_paid": "A"
    }
  ],
  "etns": [
    {
      "name": "FNB Adobe Inc - C ETN",
      "ticker": "ADETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Adobe Inc. is an American multinational computer software company. Incorporated in Delaware and headquartered in San Jose, California, it has historically focused upon the creation of multimedia and creativity software products, with a more recent foray into digital marketing software",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Adobe Inc – Q ETN",
      "ticker": "ADETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Adobe Inc. is an American multinational computer software company. Incorporated in Delaware and headquartered in San Jose, California, it has historically focused upon the creation of multimedia and creativity software products, with a more recent foray into digital marketing software",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Airbnb Inc-Class A - C ETN",
      "ticker": "BBETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Airbnb, Inc., together with its subsidiaries, operates a platform that enables hosts to offer stays and experiences to guests worldwide.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Airbnb Inc-Class A - Q ETN",
      "ticker": "BBETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Airbnb, Inc., together with its subsidiaries, operates a platform that enables hosts to offer stays and experiences to guests worldwide.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Alphabet - C ETN",
      "ticker": "ALETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Alphabet Inc. is an American multinational conglomerate headquartered in Mountain View, California. It was created through a restructuring of Google on October 2, 2015, and became the parent company of Google and several former Google subsidiaries",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Alphabet - Q ETN",
      "ticker": "ALETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Alphabet Inc. is an American multinational conglomerate headquartered in Mountain View, California. It was created through a restructuring of Google on October 2, 2015, and became the parent company of Google and several former Google subsidiaries",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Amazon - C ETN",
      "ticker": "AMETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Amazon.com, Inc. is an American multinational technology company based in Seattle, Washington, which focuses on e-commerce, cloud computing, digital streaming, and artificial intelligence.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Amazon - Q ETN",
      "ticker": "AMETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Amazon.com, Inc. is an American multinational technology company based in Seattle, Washington, which focuses on e-commerce, cloud computing, digital streaming, and artificial intelligence.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Apple - C ETN",
      "ticker": "APETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Apple Inc. is an American multinational technology company headquartered in Cupertino, California, that designs, develops and sells consumer electronics, computer software, and online services.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Apple - Q ETN",
      "ticker": "APETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Apple Inc. is an American multinational technology company headquartered in Cupertino, California, that designs, develops and sells consumer electronics, computer software, and online services.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB ASML Holding NV- C ETN",
      "ticker": "ASETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "ASML Holding N.V. (originally standing for Advanced Semiconductor Materials Lithography) is a Dutch multinational corporation founded in 1984. ASML specializes in the development and manufacturing of photolithography machines which are used to produce computer chips.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB ASML Holding NV - Q ETN",
      "ticker": "ASETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "ASML Holding N.V. (originally standing for Advanced Semiconductor Materials Lithography) is a Dutch multinational corporation founded in 1984. ASML specializes in the development and manufacturing of photolithography machines which are used to produce computer chips.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Berkshire Hathaway Inc - C ETN",
      "ticker": "BHETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Berkshire Hathaway is an American multinational conglomerate holding company headquartered in Omaha, Nebraska, United States",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Berkshire Hathaway Inc - Q ETN",
      "ticker": "BHETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Berkshire Hathaway is an American multinational conglomerate holding company headquartered in Omaha, Nebraska, United States",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB BlackRock Inc - C ETN",
      "ticker": "BRETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "BlackRock Inc. is a multinational investment company and the world's largest asset manager, with over $11 trillion in assets under management, providing investment, advisory, and risk management solutions to institutional and retail clients.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB BlackRock Inc - Q ETN",
      "ticker": "BRETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "BlackRock Inc. is a multinational investment company and the world's largest asset manager, with over $11 trillion in assets under management, providing investment, advisory, and risk management solutions to institutional and retail clients.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Booking Holdings Inc - C ETN",
      "ticker": "BKETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Booking Holdings Inc. is an American travel technology company that owns and operates several travel fare aggregators.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Booking Holdings Inc - Q ETN",
      "ticker": "BKETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Booking Holdings Inc. is an American travel technology company that owns and operates several travel fare aggregators.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Broadcom Inc - C ETN",
      "ticker": "BCETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Broadcom Inc. is an American multinational designer, developer, manufacturer, and global supplier of a wide range of semiconductor and infrastructure software products. Broadcom's product offerings serve the data center, networking, software, broadband, wireless, storage, and industrial markets.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Broadcom Inc - Q ETN",
      "ticker": "BCETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Broadcom Inc. is an American multinational designer, developer, manufacturer, and global supplier of a wide range of semiconductor and infrastructure software products. Broadcom's product offerings serve the data center, networking, software, broadband, wireless, storage, and industrial markets.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Coca Cola - C ETN",
      "ticker": "COETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "The Coca-Cola Company is an American multinational beverage corporation headquartered in Atlanta, Georgia. The Coca-Cola Company has interests in the manufacturing, retailing and marketing of non-alcoholic beverage concentrates and syrups.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Coca Cola - Q ETN",
      "ticker": "COETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "The Coca-Cola Company is an American multinational beverage corporation headquartered in Atlanta, Georgia. The Coca-Cola Company has interests in the manufacturing, retailing and marketing of non-alcoholic beverage concentrates and syrups.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Eli Lilly and Company - C ETN",
      "ticker": "LLETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Eli Lilly and Company is an American pharmaceutical company headquartered in Indianapolis, Indiana, with offices in 18 countries. Its products are sold in approximately 125 countries.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Eli Lilly and Company - Q ETN",
      "ticker": "LLETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Eli Lilly and Company is an American pharmaceutical company headquartered in Indianapolis, Indiana, with offices in 18 countries. Its products are sold in approximately 125 countries.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Facebook - C ETN",
      "ticker": "FAETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Facebook, Inc. is an American social media conglomerate corporation based in Menlo Park, California.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Facebook - Q ETN",
      "ticker": "FAETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Facebook, Inc. is an American social media conglomerate corporation based in Menlo Park, California.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Ford Motor Company - C ETN",
      "ticker": "FDETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Ford Motor Company, commonly known as Ford, is an American multinational automaker that has its main headquarters in Dearborn, Michigan, a suburb of Detroit. It was founded by Henry Ford and incorporated on June 16, 1903.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Ford Motor Company - Q ETN",
      "ticker": "FDETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Ford Motor Company, commonly known as Ford, is an American multinational automaker that has its main headquarters in Dearborn, Michigan, a suburb of Detroit. It was founded by Henry Ford and incorporated on June 16, 1903.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Goldman Sachs Group Inc - C ETN",
      "ticker": "GSETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "The Goldman Sachs Group, Inc., is an American multinational investment bank and financial services company headquartered in New York City. It offers services in investment management, securities, asset management, prime brokerage, and securities underwriting.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Goldman Sachs Group Inc - Q ETN",
      "ticker": "GSETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "The Goldman Sachs Group, Inc., is an American multinational investment bank and financial services company headquartered in New York City. It offers services in investment management, securities, asset management, prime brokerage, and securities underwriting.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB JP Morgan Chase and Co - C ETN",
      "ticker": "JPETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "JPMorgan Chase & Co. is an American multinational investment bank and financial services holding company headquartered in New York City. JPMorgan Chase is ranked by S&P Global as the largest bank in the United States and the seventh largest bank in the world by total assets, with total assets of US$3.213 trillion.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB JP Morgan Chase and Co - Q ETN",
      "ticker": "JPETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "JPMorgan Chase & Co. is an American multinational investment bank and financial services holding company headquartered in New York City. JPMorgan Chase is ranked by S&P Global as the largest bank in the United States and the seventh largest bank in the world by total assets, with total assets of US$3.213 trillion.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB LVMH Moet Hennessy Louis Vuitton SE - C ETN",
      "ticker": "LVETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "LVMH Moët Hennessy Louis Vuitton SE, commonly known as LVMH, is a French multinational holding company and conglomerate that specializes in luxury goods and has its headquarters in Paris, France.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB LVMH Moet Hennessy Louis Vuitton SE - Q ETN",
      "ticker": "LVETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "LVMH Moët Hennessy Louis Vuitton SE, commonly known as LVMH, is a French multinational holding company and conglomerate that specializes in luxury goods and has its headquarters in Paris, France.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB McDonalds - C ETN",
      "ticker": "MCETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "McDonald's Corporation is an American fast-food company, founded in 1940 as a restaurant operated by Richard and Maurice McDonald, in San Bernardino, California, United States.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB McDonalds - Q ETN",
      "ticker": "MCETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "McDonald's Corporation is an American fast-food company, founded in 1940 as a restaurant operated by Richard and Maurice McDonald, in San Bernardino, California, United States.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Microsoft - C ETN",
      "ticker": "MSETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Microsoft Corporation is an American multinational technology company with headquarters in Redmond, Washington. It develops, manufactures, licenses, supports, and sells computer software, consumer electronics, personal computers, and related services.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Microsoft - Q ETN",
      "ticker": "MSETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Microsoft Corporation is an American multinational technology company with headquarters in Redmond, Washington. It develops, manufactures, licenses, supports, and sells computer software, consumer electronics, personal computers, and related services.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Netflix - C ETN",
      "ticker": "NFETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Netflix, Inc. is an American technology and media services provider, and production company headquartered in Los Gatos, California. Netflix was founded in 1997 by Reed Hastings and Marc Randolph in Scotts Valley, California.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Netflix - Q ETN",
      "ticker": "NFETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Netflix, Inc. is an American technology and media services provider, and production company headquartered in Los Gatos, California. Netflix was founded in 1997 by Reed Hastings and Marc Randolph in Scotts Valley, California.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Novo Nordisk A/S-B - C ETN",
      "ticker": "NNETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Novo Nordisk A/S is a global healthcare company focused on diabetes and obesity care, biopharmaceuticals, and rare disease treatments, with its B shares listed on Nasdaq Copenhagen and the New York Stock Exchange.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Novo Nordisk A/S-B - Q ETN",
      "ticker": "NNETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Novo Nordisk A/S is a global healthcare company focused on diabetes and obesity care, biopharmaceuticals, and rare disease treatments, with its B shares listed on Nasdaq Copenhagen and the New York Stock Exchange.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Nvidia Corporation - C ETN",
      "ticker": "NVETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Nvidia Corporation is an American multinational corporation and technology company headquartered in Santa Clara, California, and incorporated in Delaware. It is a software company which designs and supplies graphics processing units (GPUs), application programming interfaces (APIs) for data science and high-performance computing as well as system on a chip units (SoCs) for the mobile computing and automotive market. Nvidia is also a dominant supplier of artificial intelligence (AI) hardware and software",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Nvidia Corporation - Q ETN",
      "ticker": "NVETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Nvidia Corporation is an American multinational corporation and technology company headquartered in Santa Clara, California, and incorporated in Delaware. It is a software company which designs and supplies graphics processing units (GPUs), application programming interfaces (APIs) for data science and high-performance computing as well as system on a chip units (SoCs) for the mobile computing and automotive market. Nvidia is also a dominant supplier of artificial intelligence (AI) hardware and software",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Palantir Technologies Inc A - C ETN",
      "ticker": "PTETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Palantir Technologies Inc. is an American publicly traded company that specializes in software platforms for big data analytics. Headquartered in Denver, Colorado, it was founded by Peter Thiel, Stephen Cohen, Joe Lonsdale, and Alex Karp in 2003.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Palantir Technologies Inc A - Q ETN",
      "ticker": "PTETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Palantir Technologies Inc. is an American publicly traded company that specializes in software platforms for big data analytics. Headquartered in Denver, Colorado, it was founded by Peter Thiel, Stephen Cohen, Joe Lonsdale, and Alex Karp in 2003.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Palo Alto Networks Inc - C ETN",
      "ticker": "PAETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Palo Alto Networks, Inc. is an American multinational cybersecurity company with headquarters in Santa Clara, California. The core product is a platform that includes advanced firewalls and cloud-based offerings that extend those firewalls to cover other aspects of security.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Palo Alto Networks Inc - Q ETN",
      "ticker": "PAETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Palo Alto Networks, Inc. is an American multinational cybersecurity company with headquarters in Santa Clara, California. The core product is a platform that includes advanced firewalls and cloud-based offerings that extend those firewalls to cover other aspects of security.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB PayPal Holdings Inc - C ETN",
      "ticker": "PPETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "PayPal Holdings, Inc. is an American company operating a worldwide online payments system that supports online money transfers and serves as an electronic alternative to traditional paper methods like checks and money orders.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB PayPal Holdings Inc - Q ETN",
      "ticker": "PPETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "PayPal Holdings, Inc. is an American company operating a worldwide online payments system that supports online money transfers and serves as an electronic alternative to traditional paper methods like checks and money orders.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Tesla - C ETN",
      "ticker": "TSETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Tesla, Inc. is an American electric vehicle and clean energy company based in Palo Alto, California. Tesla's current products include electric cars, battery energy storage from home to grid scale, solar products and related products and services.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Tesla - Q ETN",
      "ticker": "TSETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Tesla, Inc. is an American electric vehicle and clean energy company based in Palo Alto, California. Tesla's current products include electric cars, battery energy storage from home to grid scale, solar products and related products and services.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Visa Inc, Class A - C ETN",
      "ticker": "VSETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Visa Inc. is an American multinational financial services corporation headquartered in Foster City, California, United States. It facilitates electronic funds transfers throughout the world, most commonly through Visa-branded credit cards, debit cards and prepaid cards.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Visa Inc, Class A - Q ETN",
      "ticker": "VSETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "Visa Inc. is an American multinational financial services corporation headquartered in Foster City, California, United States. It facilitates electronic funds transfers throughout the world, most commonly through Visa-branded credit cards, debit cards and prepaid cards.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB The Walt Disney Company – C ETN",
      "ticker": "WDETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "The Walt Disney Company, commonly referred to as simply Disney, is an American multinational mass media and entertainment conglomerate headquartered at the Walt Disney Studios complex in Burbank, California.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB The Walt Disney Company - Q ETN",
      "ticker": "WDETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Single Stock Access",
      "description": "The Walt Disney Company, commonly referred to as simply Disney, is an American multinational mass media and entertainment conglomerate headquartered at the Walt Disney Studios complex in Burbank, California.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB iShares Core MSCI World - C ETN",
      "ticker": "MWETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "The Fund seeks to track the performance of the MSCI World Index - exposure to a wide range of global companies within 23 developed countries.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB iShares Core MSCI World – Q ETN",
      "ticker": "MWETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "The Fund seeks to track the performance of the MSCI World Index - exposure to a wide range of global companies within 23 developed countries.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB - iShares Global Clean Energy UCITS – C ETN",
      "ticker": "EGETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "Tracks the S&P Global Clean Energy Index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB - iShares Global Clean Energy UCITS Q ETN",
      "ticker": "EGETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "Tracks the S&P Global Clean Energy Index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB - iShares Global Water UCITS – C ETN",
      "ticker": "WWETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "Tracks the S&P Global Water Index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB - iShares Global Water UCITS - Q ETN",
      "ticker": "WWETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "Tracks the S&P Global Water Index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB – UBS MSCI World Socially Responsible UCITS - C ETN",
      "ticker": "SRETNC",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "Tracks the MSCI World Socially Responsible 5% Issuer Capped Total Return Net Index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB - UBS MSCI World Socially Responsible UCITS - Q ETN",
      "ticker": "SRETNQ",
      "type": "ETN",
      "category": "Foreign ETNs - Index Tracking",
      "description": "Tracks the MSCI World Socially Responsible 5% Issuer Capped Total Return Net Index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Bloomberg Transatlantic Top 50 Biotech NRI EUR ETN",
      "ticker": "BIOTEC",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Bloomberg Transatlantic Top 50 Biotech Price Return Index which is composed of the largest 25 companies classified in Biotech from Europe DM and North America regions.",
      "dividends_paid": "TR"
    },
    {
      "name": "Bloomberg Luxury Series 1 NRI EUR ETN",
      "ticker": "ULUXSE",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Bloomberg Luxury Series 1 Net Return Index which provides exposure to 19 companies which are among the most important players in the global luxury market.",
      "dividends_paid": "TR"
    },
    {
      "name": "Bloomberg MSCI USA IMI Metaverse Select Index Net USD ETN",
      "ticker": "METVRS",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the MSCI USA IMI Metaverse Select Index which aims to reflect the performance of companies involved in the metaverse trend, captured via subthemes including social media, digital payments, e-commerce, machine learning and artificial intelligence.",
      "dividends_paid": "TR"
    },
    {
      "name": "Bloomberg Eurozone DM Top 10 Oil & Gas NRI EUR ETN",
      "ticker": "OILGAS",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the best performing companies in the European oil and gas markets where geopolitical and environmental strife is less of a concern, giving investors valuable exposure to the cutting-edge developments and improvements on the non-renewable energy horizon.",
      "dividends_paid": "TR"
    },
    {
      "name": "Bloomberg Euronext Helios Space Index NR ETN",
      "ticker": "USPACE",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the stock market performance of companies that operate in the space industry, including developers and manufacturers of space systems, aviation, navigation, and satellite companies as well as engine manufacturers.",
      "dividends_paid": "TR"
    },
    {
      "name": "EURO STOXX 50 Net Total Return Index ETN",
      "ticker": "UBSSXF",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the EURO STOXX 50 Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "FTSE 100 Net of Tax Index ETN",
      "ticker": "UBSUKX",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the FTSE 100 Net of Tax index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "MSCI Emerging Market Net Total Return Index ETN",
      "ticker": "UEMERG",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the MSCI Emerging Market Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "MSCI Japan Net Total Return Index ETN",
      "ticker": "UJAPAN",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the MSCI Japan Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "MSCI USA Net Total Return Index ETN",
      "ticker": "UBNDDU",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the MSCI USA Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "MSCI World ESG Leaders Net Total Return Index ETN",
      "ticker": "UESGWL",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the MSCI World ESG Leaders Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "MSCI World Net Total Return Index ETN",
      "ticker": "UWORLD",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the MSCI World Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Nasdaq-100 Net Total Return Index ETN",
      "ticker": "UBSNDX",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Nasdaq 100 Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "S&P 500 Dividend Aristocrats Net Total Return Index ETN",
      "ticker": "UBDAUD",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the S&P 500 Dividend Aristocrats Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "S&P 500 Low Volatility High Dividend Net Total Return Index ETN",
      "ticker": "UBLVHD",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the S&P 500 Low Volatility High Dividend Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "S&P 500 Net Total Return Index ETN",
      "ticker": "UBSSNP",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the S&P 500 Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "S&P Kensho New Economy RAIC Net Total Return Index ETN",
      "ticker": "UBRAIC",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the S&P Kensho New Economy RAIC Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Solactive Big Data Net Total Return Index ETN",
      "ticker": "UBDATA",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Solactive Big Data Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Solactive Fintech 20 Net Total Return Index ETN",
      "ticker": "UBTECU",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Solactive Fintech 20 Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Solactive Global Family-Owned Companies Total Return Index ETN",
      "ticker": "UBFAMU",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Solactive Global Family-Owned Companies Total Return index as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Solactive Guru Net Total Return Index ETN",
      "ticker": "UBGURU",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Solactive Guru Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Solactive Robotics and Drones Net Total Return Index ETN",
      "ticker": "UBROBO",
      "type": "ETN",
      "category": "Foreign ETNs - Themed Index Tracking",
      "description": "Tracks the Solactive Robotics and Drones Net Total Return as the underlying index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Absa NewWave Platinum ETN",
      "ticker": "NEWPLT",
      "type": "ETN",
      "category": "Commodities - ETNs",
      "description": "Invests in the spot price platinum market, thus differing from the Standard Bank Platinum-Linker, which invests in platinum futures. Trades in rands on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "Absa NewWave Silver ETN",
      "ticker": "NEWSLV",
      "type": "ETN",
      "category": "Commodities - ETNs",
      "description": "Invests in silver spot market. Listed and traded in rands as \"inward investments\" on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "Standard Bank Copper ETN",
      "ticker": "SBCOP",
      "type": "ETN",
      "category": "Commodities - ETNs",
      "description": "Provides access to the copper price on world markets, using copper commodity futures traded on COMEX (traded in rands on the JSE).",
      "dividends_paid": "ND"
    },
    {
      "name": "Standard Bank Oil ETN",
      "ticker": "SBOIL",
      "type": "ETN",
      "category": "Commodities - ETNs",
      "description": "The Oil ETN is linked to the price of Brent Crude Oil price (which is more relevant in South Africa) Traded in rands on the JSE.",
      "dividends_paid": "ND"
    },
    {
      "name": "Absa NewWave GBP ETN",
      "ticker": "NEWGBP",
      "type": "ETN",
      "category": "Currencies - ETNs",
      "description": "Provides an investment in the British Pound, where the principal amount stays unchanged in Pounds. Interest accrues on a daily basis and is included in the ETN price. The price is measured against the rand, so the price can go up or down (in rands), depending on Rand/UK £ exchange rate movements. Listed as inward investments on the JSE, trades in rands.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Absa NewWave EUR ETN",
      "ticker": "NEWEUR",
      "type": "ETN",
      "category": "Currencies - ETNs",
      "description": "Same as above but provides a Euro Investment.",
      "dividends_paid": "Bi-A"
    },
    {
      "name": "Absa NewWave USD ETN",
      "ticker": "NEWUSD",
      "type": "ETN",
      "category": "Currencies - ETNs",
      "description": "Same as NewWave GBP but invests in US Dollar deposits.",
      "dividends_paid": "Bi-A"
    }
  ],
  "amcs": [
    {
      "name": "Absa 1nvest Equity AMC",
      "ticker": "ABAM1",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is linked to the ABSA Investments Equity AMC Portfolio as the Reference Portfolio. The objective of the portfolio is to exceed the performance of the FTSE/JSE All Share Index, over the longer-term (on a risk-adjusted basis).",
      "dividends_paid": "TR"
    },
    {
      "name": "AAM Multi Strategy Equity Portfolio AMC",
      "ticker": "AMC001",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The strategy aims to produce active alpha at half the volatility by exploiting market inefficiencies regardless of direction. The fund targets 70% of market returns when markets are trending up, whilst during market downturns, the strategy aims to participate 30% in bearish conditions.",
      "dividends_paid": "TR"
    },
    {
      "name": "Anchor Equity Opportunity Reference Portfolio AMC",
      "ticker": "AMC008",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Opportunity Reference portfolio, actively managed by Anchor Capital, seeks to provide good long-term returns by utilising long and short equity positions, using listed derivatives, in both local and foreign exchanges.",
      "dividends_paid": "TR"
    },
    {
      "name": "Baobab Equity Reference Portfolio AMC",
      "ticker": "AMC009",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Linked to the actively managed Baobab Equity AMC Reference Portfolio which may at any time comprise long positions in shares, ETFs and ETNs which are listed on any Recognised Exchange.",
      "dividends_paid": "TR"
    },
    {
      "name": "Blue Horseshoe Equity Portfolio AMC",
      "ticker": "AMC004",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "By process of fundamental analysis, and careful selection of securities, the reference portfolio manager, BP Bernstein, will endeavour to beat a benchmark of 60% JSE All Share Index and 40% of MSCI World Index.",
      "dividends_paid": "TR"
    },
    {
      "name": "Catalyx SA Core Hedge AMC",
      "ticker": "AMC020",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is managed by Catalyx Investments Proprietary Limited and consists of long positions in SA listed shares.",
      "dividends_paid": "TR"
    },
    {
      "name": "ClucasGray Asset Management Focussed Equity Portfolio AMC",
      "ticker": "AMC003",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Reference Portfolio Manager, ClucasGray Asset Management will actively manage the Reference Portfolio with the aim of outperforming the returns of the JSE Capped SWIX Total Return Index, over time.",
      "dividends_paid": "TR"
    },
    {
      "name": "Differential Capital Grad AMC",
      "ticker": "AMC015",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Differential Grad AMC is actively managed by Differential Capital Proprietary Limited, comprising of long and short positions in shares which are listed on a recognised exchange.",
      "dividends_paid": "TR"
    },
    {
      "name": "Differential Capital Kyrios AMC",
      "ticker": "AMC016",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Differential Kyrios AMC is actively managed by Differential Capital Proprietary Limited, comprising of long positions in shares which are listed on a recognised exchange.",
      "dividends_paid": "TR"
    },
    {
      "name": "High Street Offshore Yielding Portfolio AMC",
      "ticker": "AMC002",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The investment mandate will be to identify global multi-national companies that can generate significant cashflows that will translate into strong recurring dividend payments. In addition, the mandate will include the ability to select global companies that return capital to shareholders through active share buyback programmes. High yielding Government and corporate bonds are also used if they yield higher returns than the S&P 500 dividend yield.",
      "dividends_paid": "TR"
    },
    {
      "name": "High Street Wealth Warriors High Equity Portfolio AMC",
      "ticker": "AMC007",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Actively managed portfolio of long positions in shares, ETFs and Notes which reference fixed income securities, listed on developed market stock exchanges and the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Kudala Wealth Honey Badger AMC",
      "ticker": "AMC013",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is linked to the Kudala Wealth Honey Badger portfolio of shares and ETFs listed on global stock exchanges as well as the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "M H Capital Growth AMC",
      "ticker": "AMC018",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This investment seeks unique invest opportunities in the South African equity markets. It is best viewed as a complementary addition to an investor's existing portfolio. Investors should have the capacity to tolerate higher levels of capital volatility associated with this type of investment",
      "dividends_paid": "TR"
    },
    {
      "name": "Melville Douglas SA Inc AMC",
      "ticker": "AMC021",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Melville Douglas SA focused equity portfolio provides investors with an opportunity to gain exposure to a focused portfolio of 10-12 JSE listed companies primarily exposed to the SA economy",
      "dividends_paid": "TR"
    },
    {
      "name": "NVest Balanced Portfolio AMC",
      "ticker": "AMC006",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Actively managed by NVest Securities who will endeavour to generate returns equal to or higher than the South Africa Consumer Price Index (CPI), plus 5% per annum, over rolling 3-year periods.",
      "dividends_paid": "TR"
    },
    {
      "name": "NVest Stable Portfolio AMC",
      "ticker": "AMC005",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Actively managed by NVest Securities to reference the NVest Global portfolio which invests in global shares, ETFs, ADRs and cash.",
      "dividends_paid": "TR"
    },
    {
      "name": "NVest Global AMC Portfolio AMC",
      "ticker": "AMC012",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Actively managed by NVest Securities to reference the NVest Global portfolio which invests in global shares, ETFs, ADRs and cash.",
      "dividends_paid": "TR"
    },
    {
      "name": "NVest General Equity Portfolio AMC",
      "ticker": "AMC014",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Actively managed by NVest Securities comprises long positions in global shares, ETFs, ADRs and cash.",
      "dividends_paid": "TR"
    },
    {
      "name": "Standard Stockbroking Global Equity AMC Reference Portfolio AMC",
      "ticker": "AMC010",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio may, at any time, comprise long positions in shares and some ETFs which are listed on a recognised exchange. The Reference Portfolio Manager identifies long-term value accretive business, with either growth or value unlock potential which the Manager believes are underappreciated by the investor market.",
      "dividends_paid": "TR"
    },
    {
      "name": "Standard Stockbroking Global Equity ETF AMC Reference Portfolio AMC",
      "ticker": "AMC011",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio may, at any time, comprise long positions in ETFs which are listed on a recognised exchange. The Reference Portfolio Manager identifies well-diversified selected ETFS to target attract segments of global equity markets.",
      "dividends_paid": "TR"
    },
    {
      "name": "STANLIB Multi-Asset SA DAA Strategy AMC",
      "ticker": "AMC017",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is managed by Stanlib Asset Management Proprietary Limited, comprises long position in equities and bonds which are listed on a recognised exchange",
      "dividends_paid": "TR"
    },
    {
      "name": "Absa (Global Equity) AMC",
      "ticker": "UABSPA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Primary object of the portfolio is to provide above-average total returns over the medium to long-term by investing in shares listed offshore.",
      "dividends_paid": "TR"
    },
    {
      "name": "Absa Global Growth (Private Client Portfolios) AMC",
      "ticker": "UPCHPA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Includes stocks/ETFs from a broad range of DM & EM indices/ETFs across multiple foreign asset classes (equity, Thematic, Property, Bonds, Commodities).",
      "dividends_paid": "TR"
    },
    {
      "name": "Activ8 Growth Portfolio AMC",
      "ticker": "UA8GRO",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The portfolio will invest in a combination of local and global equity shares, ETFs and indices with a flexible mandate, and will be actively managed by allocating capital between asset classes, instruments and regions.",
      "dividencies_paid": "TR"
    },
    {
      "name": "Advantage Solutions (Pty) Ltd Biggles Worldwide Flexible Portfolio AMC",
      "ticker": "BIGGLS",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Biggles Worldwide Flexible AMC, managed Advantage Solutions (Pty) Ltd, is designed to achieve substantial long-term capital growth, with a target return of SA CPI +4% over any rolling7-year period. It benchmarks a worldwide allocation of 70% to equities and 30% to fixed income.",
      "dividends_paid": "TR"
    },
    {
      "name": "Advantage Solutions (Pty) Ltd Global Opportunities Portfolio AMC",
      "ticker": "GLOBOP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by Advantage Solutions (Pty) Ltd, this AMC is designed to achieve substantial long-term capital growth, with a target return of G7 CPI + 5% over any rolling 10-year period. 85% minimum exposure to growth assets at all times.",
      "dividends_paid": "TR"
    },
    {
      "name": "Advantage Solutions (Pty) Ltd SA Quality Core Portfolio AMC",
      "ticker": "SAQUAL",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio, managed by Advantage Solutions (Pty) Ltd, is tailored for investors with a high-risk profile, seeking substantial long-term growth. It leverages a rigorous rules-based and quantitative process to construct a robust collection of what they believe to be the highest-quality companies, listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Adviceworx SA Opportunities Portfolio AMC",
      "ticker": "ADXOPP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The investment strategy seeks to invest in a select group of quality South African and international companies with the potential to generate earnings and profit growth above the market.",
      "dividends_paid": "TR"
    },
    {
      "name": "AnBro Capital (Dynamic Compound Portfolio) AMC",
      "ticker": "ANCOMP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Invests in companies that pay dividends which are higher than the average of the MSCI Global Investable indices. A portfolio yield of 4% per annum, or higher, is targeted, before costs.",
      "dividends_paid": "TR"
    },
    {
      "name": "AnBro Capital (Global Equity) AMC",
      "ticker": "UNICRN",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "International Unicorn Portfolio (USD) – aims to provide investors with the opportunity to invest in a hard currency portfolio focused on the next generation of listed founder-managed, start-up (Unicorn) businesses.",
      "dividends_paid": "TR"
    },
    {
      "name": "AnBro Titans Portfolio AMC",
      "ticker": "TITANS",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio focuses on investing in the largest and most successful company in eleven industries within the US S&P index. The objective is to invest in leading companies that dominate their respective industries and thereby provide benefits to shareholders such as capital returns, dividends, extremely high quality and lower overall volatility than the S&P 500.",
      "dividends_paid": "TR"
    },
    {
      "name": "AnBro World's Biggest Brands Portfolio AMC",
      "ticker": "BRNDZ",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Is a portfolio of the World's most valuable brands. The portfolio is rebalanced annually to reflect the 100 most valuable companies by brand valuation.",
      "dividends_paid": "TR"
    },
    {
      "name": "Boutique Global Equity Portfolio AMC",
      "ticker": "BAMGCF",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by Boutique Asset Management, this portfolio aims to deliver an actively managed global equity portfolio that seek to achieve capital growth over the long-term while benchmarking the MSCI ACWI index. The strategy focuses on companies with superior intrinsic value and sustainable competitive advantages.",
      "dividends_paid": "TR"
    },
    {
      "name": "Boutique Hummingbird Portfolio AMC",
      "ticker": "BAMHUM",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by Boutique Asset Management, this portfolio aims to achieve capital growth over the long-term while managing risk through a disciplined process. The portfolio consists of shares listed on the JSE and benchmarks the FTSE/JSE All Shares index. The strategy focuses on mid- and small-sized companies that are established and profitable but meaningfully priced; large-cap stocks can be included in the portfolio in instances where substantial investment return is offered",
      "dividends_paid": "TR"
    },
    {
      "name": "Capital Link Partners (Pty) Ltd Asia Portfolio AMC",
      "ticker": "CLPASI",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Uses fundamental analysis techniques to identify stocks in the developed markets MSCI Global Investable indices that offer value. The selection process focusses on companies operating in Asia.",
      "dividends_paid": "TR"
    },
    {
      "name": "Capital Link Partners (Pty) Ltd Asia Growth Portfolio AMC",
      "ticker": "ASIAGR",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The portfolio and investment mandate focusses on Asia (ex. Japan). The portfolio is allocated in countries according to the size (GDP) and growth of GDP and is capped at two times the average weight of all countries to prevent concentration.",
      "dividends_paid": "TR"
    },
    {
      "name": "Cast Iron Global Special Situation Equity Portfolio AMC",
      "ticker": "UCIGEP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This unique investment portfolio is a focused portfolio with a strategy that aims to identify and exploit special situations that arise from time to time, e.g. company re-organisations, delistings, share buy-backs, special dividends, etc.",
      "dividends_paid": "TR"
    },
    {
      "name": "Coherent Capital Management (Pty) Ltd (Global Commodity Investment Portfolio) AMC",
      "ticker": "CCMGCZ",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Offers risk managed access to the individual components of the agricultural, energy and metal sectors of the commodity asset class, to provide a risk-adjusted commodity basket portfolio.",
      "dividends_paid": "TR"
    },
    {
      "name": "Coherent Capital Management (Pty) Ltd (Coherent Fuel Hedge Portfolio) AMC",
      "ticker": "FUELZA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Offers risk managed access to the individual components of the energy sector of the commodity asset class, to provide the fuel consumer with protection against rising fuel prices while retaining the benefit of falling fuel prices.",
      "dividends_paid": "TR"
    },
    {
      "name": "Denker Capital Global Opportunities Portfolio AMC",
      "ticker": "DNKGLO",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Invests in the equity of small and medium sized companies, predominantly based in global developed markets, which trade at attractive valuations relative to their long-term intrinsic value.",
      "dividends_paid": "TR"
    },
    {
      "name": "Denker Capital (Small Cap Opportunities Portfolio) AMC",
      "ticker": "DNKOPP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Invests in a focussed portfolio of small capitalisation stocks listed on the JSE and world stocks listed on developed market exchanges. Also uses ETFs listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Efficient Group (Global Equity) AMC",
      "ticker": "UEFPCA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Tracks the EFPC Global House View portfolio, a well-diversified global equity portfolio.",
      "dividends_paid": "TR"
    },
    {
      "name": "Efficient Private Local Model Portfolio AMC",
      "ticker": "UEFPCL",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "EFPC is an advisor-centric, global investment specialist firm for high net-worth individuals. The universe for this AMC is the MSCI Global Investable Index, plus ETFs listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Excelsia Emerging Market Equity Portfolio AMC",
      "ticker": "EXEMEQ",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The investment strategy seeks to provide medium to long-term capital growth through investment in listed equity and equity-related securities in emerging markets, which will endeavour to deliver solid performance and average or lower volatility over time.",
      "dividends_paid": "TR"
    },
    {
      "name": "FNB Local Select Portfolio AMC",
      "ticker": "FNBLSP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Design for use as part of the segregated model portfolio and complement the holdings in the overall portfolio strategy - the portfolio is selected from shares and ETFs listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Grovepoint Investment Management AMC",
      "ticker": "GIMLPC",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The portfolio invests in listed credit vehicles managed by leading private credit managers. Underlying loans are typically floating rate, senior secured obligations of middle market U.S. corporates.",
      "dividends_paid": "TR"
    },
    {
      "name": "Independent Investment Solutions (Pty) Limited (i²) AMC",
      "ticker": "ISGLOB",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Independent Investment Solutions (Pty) Ltd (i²) offers its i² global strategy portfolio, which invests in developed markets (MSCI Global Investible Index), plus shares listed on the Main Board of the JSE. The Note is classified as foreign for exchange control purposes.",
      "dividends_paid": "TR"
    },
    {
      "name": "Mergence Global Quant Equity Portfolio AMC",
      "ticker": "MERGE",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The portfolio, issued by Mergence Portfolio Management, a Cape Town based asset manager, covers a diverse product range across both global public and private markets, spanning equity, multi-asset funds, infrastructure, debt and private equity funds, which focus on systematic quality, value, and momentum investment styles.",
      "dividends_paid": "TR"
    },
    {
      "name": "Mergence Global Quant Equity B Portfolio AMC",
      "ticker": "MERGQB",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Mergence Global Quant Equity B portfolio provides diversified access to capital growth opportunities across the world's developed economies, with the fund strategy driven by quantitative research and supported by risk controls.",
      "dividends_paid": "TR"
    },
    {
      "name": "Momentum (Global Equity) AMC",
      "ticker": "UMMIEA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Invests in Momentum Securities' International Equity Portfolio, which has a global focus determined to maximise",
      "dividends_paid": "TR"
    },
    {
      "name": "Momentum (Global Equity) AMC",
      "ticker": "UMMIEB",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Invests in Momentum Securities' International Equity Portfolio, which has a global focus determined to maximise",
      "dividends_paid": "TR"
    },
    {
      "name": "Nedbank Private Wealth Global Portfolio AMC",
      "ticker": "UNPWGP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is focused on long-term capital appreciation and income growth and will include global equities and indices, ETFs and cash.",
      "dividends_paid": "TR"
    },
    {
      "name": "Old Mutual Wealth Global Trust Company AMC",
      "ticker": "UOMWPA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Includes stocks/ETFs from a broad range of DM & EM indices/ETFs across multiple foreign asset classes (equity, Thematic, Property, Bonds, Commodities).",
      "dividends_paid": "TR"
    },
    {
      "name": "Ordian Global Multi-Asset Portfolio AMC",
      "ticker": "ORDGMU",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This AMC aims to deliver a systematic, data-driven investment strategy that combines fundamental analysis with value investing principles. This methodology aims to identify undervalued stocks with strong financial performance and meaningful potential for future growth.",
      "dividends_paid": "TR"
    },
    {
      "name": "Private Client Global Brands Portfolio AMC",
      "ticker": "UBRAND",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by Private Client Asset Management (Pty) Ltd, a Cape Town based asset manager, invests in the world's most successful brands, within the MSCI Global Investible Market Index. The Note is classified as foreign, for local exchange control purposes.",
      "dividends_paid": "TR"
    },
    {
      "name": "Private Client MidCap Opportunities Portfolio AMC",
      "ticker": "PCMCOP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by the Private Client' s division of Old Mutual Wealth, the MidCap Investment Opportunities Portfolio invests in high growth global and South African mid-cap companies.",
      "dividends_paid": "TR"
    },
    {
      "name": "PWM Balanced Portfolio AMC",
      "ticker": "MRPWMB",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by PWM Wealth (Pty) Ltd, this portfolio's mission is to provide a strategic mix of bonds, stocks and ETFs across global markets.",
      "dividends_paid": "TR"
    },
    {
      "name": "SAAM Global Growth Portfolio AMC",
      "ticker": "SAAGG",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Issued by SA Asset Management, a Pretoria based asset manager. These portfolios focus on the active management of client assets in a range of local and global funds and strategies to deliver real returns in focused portfolios of high-quality growth stocks.",
      "dividends_paid": "TR"
    },
    {
      "name": "SAAM Local Growth Portfolio AMC",
      "ticker": "SAALG",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Issued by SA Asset Management, a Pretoria based asset manager. These portfolios focus on the active management of client assets in a range of local and global funds and strategies to deliver real returns in focused portfolios of high-quality growth stocks.",
      "dividends_paid": "TR"
    },
    {
      "name": "SBT Global Flexible Portfolio AMC",
      "ticker": "SBTGFP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by Numoro (Pty) Ltd, a Cape Town based asset manager, the AMC aims to deliver a systemic, data-driven investment strategy the combines fundamental analysis with value investment principles, which identifies undervalued stocks with strong financial performance and potential for future growth. The investment universe includes global developed markets and shares listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Southern Rock Allegro Portfolio AMC",
      "ticker": "ALEGRO",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is managed by Southern Rock Capital Limited, a privately owned investment firm, registered in Mauritius. The investment strategy seeks to invest in companies that exhibit strong price momentum.",
      "dividends_paid": "TR"
    },
    {
      "name": "Southern Rock SA Allegro Portfolio AMC",
      "ticker": "ALEGSA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This portfolio is managed by Southern Rock Capital Limited, a privately owned investment firm, registered in Mauritius. The investment strategy seeks to invest in JSE listed companies that exhibit strong price momentum.",
      "dividends_paid": "TR"
    },
    {
      "name": "STANLIB Strategy 4 Portfolio AMC",
      "ticker": "STALB4",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This AMC is earmarked to target opportunities that are closely aligned to the domestic consumer through shares that are listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "STANLIB Strategy 5 Portfolio AMC",
      "ticker": "STALB5",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "This AMC gains exposure to the SA markets and energy sectors, through shares listed on the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Strategiq (Global Equity) AMC",
      "ticker": "USQCPA",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Comprises 30 global companies, equally weighted and rebalanced quarterly, subject to maximum and minimum deviation thresholds. Stock selection focuses on a rules-based quantitative approach as the primary strategy.",
      "dividends_paid": "TR"
    },
    {
      "name": "UBS AMC Excelsia Global Equity Portfolio AMC",
      "ticker": "UEXGEP",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Benchmark: MSCI All Country World Index.",
      "dividends_paid": "TR"
    },
    {
      "name": "UBS AMC FNB Global Equity AMC",
      "ticker": "FNBGEG",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Global Select ETNs aim to achieve long-term capital growth over the economic cycle by selecting leading companies globally that benefit from sustainably growing total return profiles supported by best-in-class management and solid balance sheets.",
      "dividends_paid": "TR"
    },
    {
      "name": "UBS AMC FNB Global Select AMC",
      "ticker": "FNBGSE",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The Global Select ETNs aim to achieve long-term capital growth over the economic cycle by selecting leading companies globally that benefit from sustainably growing total return profiles supported by best-in-class management and solid balance sheets.",
      "dividends_paid": "TR"
    },
    {
      "name": "UBS AMC Momentum Global Select Portfolio AMC",
      "ticker": "UMMIES",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Invests in Momentum Securities' International Sharia Aligned Equity Portfolio. This portfolio has a global focus determined to maximise risk adjusted returns to investors over the medium to long-term by investing in concentrated listed equity positions.",
      "dividends_paid": "TR"
    },
    {
      "name": "Unum Capital QuadMatic SA Equity Portfolio AMC",
      "ticker": "UUQUAD",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "Managed by Unum Capital (Pty) Ltd, a Pretoria based asset manager, this portfolio invests in JSE large and mid cap shares, listed on the Main Board of the JSE.",
      "dividends_paid": "TR"
    },
    {
      "name": "Unum Capital (Pty) Ltd Global Small/MidCap Equity Portfolio AMC",
      "ticker": "UUGSMC",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The portfolio aims to outperform its benchmark, the MSCI World Small Cap Index, both on a relative and risk adjusted basis, over the longer-term.",
      "dividends_paid": "TR"
    },
    {
      "name": "Unum Capital (Pty) Ltd Small/MidCap SA Equity Portfolio AMC",
      "ticker": "UUSMC",
      "type": "AMC",
      "category": "Actively Managed Certificates (AMCs)",
      "description": "The portfolio aims to outperform its benchmark, the FTSE/JSE MidCap Index (J201), both on a relative and risk adjusted basis, over the longer-term.",
      "dividends_paid": "TR"
    }
  ]
}
```
