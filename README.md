# Wildloom

Online clothing store for Wildloom (Comilla, Bangladesh). A static website hosted on GitHub Pages.

## Files
- `index.html`: the storefront (cart, checkout, bKash / Nagad / cash on delivery)
- `products.json`: the product list shown on the website
- `admin.html`: the owner's admin page (add products, change prices, upload photos)
- `images/`: product photos uploaded from the admin page

## Manage products
Open `admin.html` on the live site (for example `https://<username>.github.io/<repo>/admin.html`), sign in with a GitHub fine-grained access token that has Contents: Read and write on this repository, make changes, and press Publish changes. The site updates in 1-2 minutes.

## Other settings
Delivery charges and payment numbers are in the `CONFIG` section near the bottom of `index.html`.

## How orders work
The customer fills in delivery details, pays the merchant number (or chooses cash on delivery), and sends the generated order summary to the Wildloom Messenger page. Wildloom checks the TrxID in the merchant app and confirms the order.
