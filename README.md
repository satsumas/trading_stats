## iPython notebook for benchmarking trading strategies

The notebook outputs statistics on the performance of
your cryptocurrency trading algorithm on [GDAX](https://www.gdax.com/). By default, the notebook shows trading in BTC
and EUR, but can be adapted to any currency pair. 


1. Clone this repository
2. Give the local repository access to your GDAX API keys:

    Create a file, `env.sh`, in `btc_trading strategy` with the format:

   `export COINBASE_SECRET="<your-coinbase-secret>"`
`export COINBASE_KEY="<your-coinbase-key>"`
`export COINBASE_PASSPHRASE="<your-coinbase-passphrase>"`

   **make sure you _don't_ reveal env.sh -- it contains your secrets!**

3. Run the iPython Notebook `stats_last_n_days.ipynb`, filling in the indicated field for `n`,
to see performance statistics for your trading algorithm versus holding the same 
currency over the same time period. 

## Sample output

![Sample figure produced by the notebook](/sample_output.png)