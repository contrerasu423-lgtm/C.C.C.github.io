````markdown
```markdown
How to edit PayPal buttons, test orders, and fulfill with Printful

1) Edit product title/price
   - Open index.html and find the product form for each product.
   - Update the item_name and amount values to match the product & price you want.

2) Test a purchase
   - Make a small test purchase with a real PayPal account to confirm buyer email and shipping info arrive.
   - Alternatively, use PayPal Sandbox (developer.paypal.com) to test without real charges.

3) After an order arrives
   - Check the PayPal notification / email: you’ll see buyer name and shipping address.
   - In Printful, create a new order manually:
     - Choose the correct Printful product & variant.
     - Enter the buyer shipping address exactly as shown by PayPal.
     - Upload/choose the correct print file if needed and confirm print placement.
     - Pay Printful the production + shipping cost.
   - Printful will print and ship; they’ll provide tracking that you can send to the buyer.

4) SKU mapping spreadsheet (recommended)
   - Keep a small spreadsheet (CSV) with: sku, product_name, printful_product_id, sizes/colors mapping.
   - This makes manual order creation faster.

5) Shipping & timing messaging
   - Add a short note on each product card: "Allow 5–10 business days for production + shipping."
   - This sets expectations since you’re creating orders manually.

6) Replacing with PayPal-generated buttons (optional)
   - In your PayPal business account: Tools → PayPal Buttons → Create “Buy Now”.
   - Use PayPal’s generated HTML if you want hosted buttons or button images.
   - Replace the form in index.html with PayPal’s generated code if desired.

If you want, I can:
- Walk you through a live test purchase step-by-step.
- Add a shipping cost field into the PayPal forms.
- Add size dropdowns to forms (adds a form field that records the size in the order notes).
```
````