# base65
Python: Checking Contract Creator Wallet
tx = w3.eth.get_transaction("0x...")
print("Creator:", tx["from"])
