Materials for the article "Construct Bollinger Band Trend with Elasticsearch" in Medium

The following steps have been tested with Elasticsearch Server v7.10.1

Create an index, fidelity28_fund and the corresponding data are populated. The data for the index, fidelity28_fund, is coming from IEX (Investors Exchange) with the 28 Fidelity commission-free ETFs selected for demo purpose. The time range picked is between 2020-12-15 and 2021-05-31.

./fidelity28_index.sh

After the indices are created and the data are populated, Bollinger Band Width of "Fidelity Low Volatility Factor ETF" (FDLO) is calculated.

./fdlo_bbtrend.sh
