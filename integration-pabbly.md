# Pabbly

- [Connect Pabbly to OrderForms](#connect)

<a name="connect"></a>

## How to connect Pabbly to OrderForms

- in OrderForms, ensure you have a merchant connected and have at least one product to test.
- Navigate to [https://connect.pabbly.com/dashboard](https://connect.pabbly.com/dashboard) and create a new workflow
- Choose app 'OrderForms' & connect the app if needed (using your OrderForms credentials if not already logged in)
- Select trigger 'Order Created'
- Click 'Save & Send Test Request'
- Navigate to [https://app.orderforms.com/products](https://app.orderforms.com/products) and click on any product
- Ensure the product status is 'Test'. We also recommend that you add a pricing option with a price of `0` to [avoid application fees during testing](/docs/{{version}}/products#product-testing).
- Click on 'View' to the upper right to preview the product checkout page
- Order the product
- Data will be sent to Pabbly
- Configure your desired action in Pabbly
