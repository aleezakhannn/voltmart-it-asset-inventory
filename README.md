# VoltMart IT Asset Inventory

This CSV lists VoltMart's IT assets, built by extending the AutoFix Workshop inventory structure and adding VoltMart-specific assets: POS terminals, an inventory database server, Wi-Fi access points, and admin workstations.

## Columns
- **Asset ID** - unique identifier for each asset
- **Name** - descriptive name of the asset
- **Type** - category of asset (workstation, peripheral, network equipment, etc.)
- **Owner** - the staff role responsible for the asset
- **Business Value** - how important the asset is to daily operations (Low/Medium/High)
- **Sensitivity** - risk level if the asset or its data were compromised (Low/Medium/High)

## Assumptions
- Owners are assigned by realistic staff role (Store Manager, IT Admin, Store Associate) rather than named individuals.
- Business Value and Sensitivity are independent scores - an asset can be high value but low sensitivity, or vice versa.
- The list totals 16 assets, covering hardware, network, payment, and security equipment.
