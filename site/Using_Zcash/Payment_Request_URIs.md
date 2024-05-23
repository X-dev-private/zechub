# Exploring Zcash Payment Request URIs

## Overview of Dynamic QR Codes

URI stands for Universal Resource Identifier. They are QR codes that act as unique sequence characters that identify an abstract or physical resource like resources on a web page, mail address, books, etc.Zcash wallets that recognize this format and construct transactions by either clicking links on web pages or scanning QR codes. Say you have an online coffee shop, your customers can make purchases by scanning these QR codes with their Zcash wallet with a prefilled price and order number.

## Use Cases of Payment Requests 

Online Shopping Checkout: Payment requests are initiated by customers during online purchases.

Hotel and Accommodation Bookings: Various booking platforms leverage payment request URLs for hotel reservations.

Online Bill Payments: Utility companies use payment request URLs to enable customers to offset their bills seamlessly. 

Event Ticket Purchases: Event organizers across borders use this mechanism to make ticket purchases easier.

P2P Payments: Individuals can easily send payment requests to family and friends via messaging apps, with payment links embedded in the messages.

## Code Example

[ZIP 321](https://zips.z.cash/zip-0321) defines how to construct your own custom payment URI. 

**Valid Example**: zcash:address?amount=1&memo=base64urlencodedtext&message=Thank%20you%20for%20your%20purchase

### Mobile Wallet Guide

Below is a step-by-step guide to creating a unique QR code; this method is exclusively for YWallet users:

Firstly, open your YWallet then hit the QR code button.

![step-1](https://i.ibb.co/cNZXj6b/Screenshot-2024-1.png)

Check the following address types, fill in your desired amount, and enter your memo preferences.

![step-2](https://i.ibb.co/MVpDHMK/Screenshot-3.png)

Finally, click the QR code, then hit save - boom! You can now share your QR code with friends or social media communities to initiate transactions.

![step-3](https://i.ibb.co/rpLgJ7P/Screenshot-4.png)
