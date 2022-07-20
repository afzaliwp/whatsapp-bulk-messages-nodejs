# whatsapp-bulk-messages
Send Bulk messages in WhatsApp using NodeJS.

**This is not using an official API.**

#Steps to install
1. Run `npm install --ignore-scripts`
2. Run `cd node_modules/wbm/node_modules/puppeteer`
3. Run `node install.js` and wait for downloading Chromium.
4. Run `cd ../../../..`
5. Run `node index.js`

You can add you Excel (xlsx) files in public folder.
In `index.js` file, you should set the path to your xlsx file and set your message.

**In your xlsx file, you should always have a column called `phone`**
You can add other columns in your xlsx file such as **name** and use it in your message like `Hi {{name}}`.

**Note that you should add numbers with country codes.**
