# Pabbly

- [How To](#how-to)

<a name="how-to"></a>

## How to connect Pabbly to OrderForms

- Navigate to https://app.orderforms.com/login and sign in using email address support@pabbly.com and your test account password
- Navigate to https://app.orderforms.com/settings/merchants and connect a merchant

> **Warning**  
> **Warning: Any merchants other than Stripe will incur a fee charge even in test mode since we are unable to determine the mode at the merchant level!**

- Navigate to https://connect.pabbly.com/dashboard and create a new workflow
- Choose app 'OrderForms' & connect the app if needed using your OrderForms credentials
- Select trigger 'Order Created'
- Click 'Save & Send Test Request'
- Navigate to https://app.orderforms.com/products and click on the 'Test Product'
- Click on 'View' to the upper right to preview the product checkout page
- Order the Test Product
- Data will be sent to the Pabbly webhook
- Configure your desired action