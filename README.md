# skfolio Masterclass 01 - Foundations & ETF Data

**by The Chart Truth**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thecharttruth/skfolio-masterclass/blob/main/notebooks/skfolio_masterclass_01_foundations_etf_data_by_thecharttruth.ipynb)

Start here if you want a beginner-friendly path into ETF portfolio research with Python, Google Colab, and [skfolio](https://github.com/skfolio/skfolio).

This first notebook is completely free. It teaches the data foundation before any portfolio optimization: how to load a public ETF dataset, inspect coverage and liquidity, reshape prices, convert prices into returns, and begin reading correlation behavior.

## What You Will Learn

- How to open and run a professional notebook in Google Colab.
- Why portfolio tools usually work with returns instead of raw prices.
- How to validate ETF data before trusting it.
- How to build a clean price matrix and return matrix.
- How coverage, liquidity, return distributions, and correlations shape portfolio research.
- How the first notebook prepares the ground for skfolio portfolio objects in Notebook 02.

## How To Use This Notebook

1. Click **Open In Colab** at the top of this page.
2. Colab opens a runnable version of the notebook.
3. In Colab, choose **Runtime > Run all** for the first pass.
4. If you want to edit or keep your own version, choose **File > Save a copy in Drive**.
5. Your copy is yours. The original GitHub notebook stays unchanged unless you have write access to this repository.

You do not need a broker login, paid data subscription, Hugging Face account, or private API key for the default path.

## Why GitHub First?

GitHub is the public home for the project. Colab is where learners run the notebook.

Sharing the GitHub link is usually better than sharing only the live Colab link because learners can see what the notebook is, how to use it, and where to open it safely. The Colab badge brings them directly into the runnable notebook.

Learners can experiment freely in Colab, but they will not overwrite the original GitHub notebook. To save edits permanently, they need to make their own Drive copy.

## What Is In This Repo

- `README.md`: how to open and use the notebook.
- `notebooks/`: the public Notebook 01 file.
- `data/README.md`: short note explaining where the notebook data comes from.

## Data

The notebook downloads public teaching data from Hugging Face Datasets:

- Dataset: `thecharttruth/etf-data`
- Included files: ETF prices, metadata, liquidity rankings, market-index context, and a manifest.

The data is for education and research workflow practice. It does not include account data, holdings, orders, transactions, raw broker responses, or credentials.

## Credits

This project is independent educational material by **The Chart Truth**.

Special thanks to the [skfolio](https://github.com/skfolio/skfolio) project and contributors for building open-source portfolio optimization tools for Python.

## Educational Disclaimer

This notebook is for education only. It is not financial advice, investment advice, trading advice, or a recommendation to buy or sell any security. Historical data does not guarantee future results.

## Support The Series

If this free notebook helps you, please support The Chart Truth on social media by following, liking, commenting, or sharing. That signal helps decide how quickly Notebook 02 and the rest of the masterclass are released.

- X: [@thecharttruth](https://x.com/thecharttruth)
- YouTube: [@TheChartTruth](https://www.youtube.com/@TheChartTruth)
