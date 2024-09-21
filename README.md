# Analyzing the Top 10 Ethereum NFTs Using Dune API

You can find the complete guide on the Dune blog [here](https://dune.com/blog/complete-guide-analyzing-the-top-10-ethereum-nfts-using-dune-api).

This python script integrates with the Dune Analytics API to retrieve data about the top 10 NFT collections by volume within a specified date range. It prompts the user to input the start and end dates for the query, loads the DUNE API key from a `.env` file, and runs the query using the `dune_client` library. It then displays the results DataFrame and creates visualizations using Seaborn for better data representation.

You can find the sql query that this script runs in `SQL QUERY/query_sql.sql` file.

The flowchart below outlines the process of the Python script designed to retrieve and display Ethereum NFT data from Dune, starting from loading the API key to graphing the trading volumes.
<p align="center">
  <img src="https://github.com/Toufik-BHM/Top-10-Ethereum-NFTs-with-Dune-Analytics-API/assets/157906071/ef2ece8f-de53-4761-af12-dcc31274d430" alt="Flowchart Description" width="600"/>
</p>
