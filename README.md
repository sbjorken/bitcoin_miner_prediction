# Bitcoin miner prediction
Predict whether an address for a Bitcoin coinbase transaction belongs to a mining pool or not. The bitcoin blockchain data has been downloaded from a Google BigQuery dataset that can be found [here](https://www.kaggle.com/bigquery/bitcoin-blockchain). Coinbase signatures related to miners (the target variable for the prediction) have been taken from [here](https://en.bitcoin.it/wiki/Category:Pool_Operators) and [here](https://gist.github.com/denpamusic/e90929485be3282ce0aebd4f2fd1f709).

The model reliably predicts most mining pool addresses with only a few false positives and negatives.  
