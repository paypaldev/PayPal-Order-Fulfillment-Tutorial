![PayPal Developer Cover](https://github.com/paypaldev/.github/blob/main/pp-cover.png)

<div align="center">
  <a href="https://twitter.com/paypaldev" target="_blank">
    <img alt="Twitter: PayPal Developer" src="https://img.shields.io/twitter/follow/paypaldev?style=social" />
  </a>
  <br />
  <a href="https://twitter.com/paypaldev" target="_blank">Twitter</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://www.paypal.com/us/home" target="_blank">PayPal</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://developer.paypal.com/home" target="_blank">Docs</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://github.com/paypaldev" target="_blank">Code Samples</a>
    <span>&nbsp;&nbsp;-&nbsp;&nbsp;</span>
  <a href="https://dev.to/paypaldeveloper" target="_blank">Blog</a>
  <br />
  <hr />
</div>

# PayPal Order Fulfillment Tutorial

This repo contains example code for a standard PayPal integration using both the JS SDK and node.js that demonstrates how to fulfill successful orders for an e-book using SendGrid and the PayPal REST API.

Follow along with the YouTube video, [How to Automate Order Fulfillment with Node.js and SendGrid](https://youtu.be/zIuiB5qdbgQ)

## Instructions

1. [Signup for a free Sendgrid Account](https://signup.sendgrid.com/), create a sender identity, and in Settings, create an API Key
1. Replace `test` in `public/index.html` with your app's client-id
1. Create a file called `.env` and add the following:

```
CLIENT_ID=<YOUR_CLIENT_ID>
APP_SECRET=<YOUR_APP_SECRET>
SENDGRID_API_KEY=<YOUR_API_KEY>
```

1. Run `npm install`
1. Run `npm start`
1. Open http://localhost:8888

## Resources

https://www.twilio.com/blog/sending-email-attachments-with-sendgrid is a fairly comprehensive tutorial which covers a similar topic.

## PayPal Developer Community

The PayPal Developer community helps you build your career, while also improving PayPal products and the developer experience. You’ll be able to contribute code and documentation, meet new people and learn from the open source community.

- Website: [developer.paypal.com](https://developer.paypal.com)
- Twitter: [@paypaldev](https://twitter.com/paypaldev)
- Github: [@paypal](https://github.com/paypal)
