Fork from https://github.com/zaivanza/layerzero_tx_checker


# LayerZero TX Checker  :

Create a virtual environment :
`python3 -m venv .venv`

Install :
`pip3 install -r requirements.txt`


# Configuration :
1. Put your wallet adress into `wallets.txt`.
2. In the data folder, write out the API keys for the scans into text files. To do this, you need to register (links below) and create a key. One key is enough for each scan. Enter the keys line by line. Increasing the number of keys will only increase the parsing speed :
- `arb_api.txt` : https://arbiscan.io/myapikey
- `avax_api.txt` : https://snowtrace.io/myapikey
- `bsc_api.txt` : https://bscscan.com/myapikey
- `opt_api.txt` : https://optimistic.etherscan.io/myapikey
- `eth_api.txt` : https://etherscan.io/myapikey
- `polygon_api.txt` : https://polygonscan.com/myapikey
- `ftm_api.txt` : https://ftmscan.com/myapikey
- `scroll_api.txt` : https://scrollscan.com/myapikey
1. You can change values of the variables to suit your needs into `setting.py` 
- `CSV_WRITE_CHAINS` - True if you need to write information about the number of transactions for each network to CSV.
- `CSV_WRITE_PROTOCOLS` - True if you need to write information about the number of transactions for each protocol to CSV.
- `FILE_NAME` - You can change the name to what you want.

# Result :
After executing the script, the data will be written into a CSV file. You can import it into Google Spreadsheet to visualize properly your results.

OR 

You can install "CSV to Table" script into VSCode.


# Infos : 

Twitter : 0xjust1.eth

Tips : 0xA3Cb5B568529b27e93AE726C7d8aEF18Cd551621

This script will be update frequently with new protocols & chains to keep update to check activity on LayerZero.
