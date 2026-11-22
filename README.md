# Wildloom

Online clothing store for Wildloom (Comilla, Bangladesh). A single static page: `index.html`.

## Update products, prices and contact details
Open `index.html` and edit the `CONFIG` and `PRODUCTS` lists near the bottom of the file.

- `CONFIG.pay.bkash` / `CONFIG.pay.nagad`: merchant numbers. Leave empty to hide that method.
- `CONFIG.shipHome`, `shipOther`, `freeOver`: delivery charges.

## How orders work
The customer fills in delivery details, pays the merchant number (or chooses cash on delivery), and sends the generated order summary to the Wildloom Messenger page. Wildloom checks the TrxID in the merchant app and confirms the order.

## Publish
Upload the file to GitHub, then Settings > Pages > Deploy from a branch > `main` / root.
