Web Scrapping Project
# Web Automation Project - Price Search

### Objective: develop a project where we have to use web automations with Selenium to get the information we need

### How will it work:

- Imagine that you work in the purchasing area of ​​a company and need to compare suppliers for your inputs/products.

- At this time, you will constantly search the websites of these suppliers for the products available and the price, after all, each of them can promote at different times and with different values.

- Your goal: find the cheapest product and update it in a spreadsheet.
- If the value is 20% (or more) below the original price, we also want to be notified by email so that we can act quickly and take advantage of this promotion.

- In our case, we are going to use common products on sites like Amazon, Magazine Luiza and Lojas Americanas, but the idea is the same.

### What do we have available?

- Product Sheet, with the names of the products and the link in each store, in addition to the original registered price.

### What should we do:

- Register the lowest price found in the Current Price column and in the Local Column the name of the website where this price was found
- Send an email for purchases with notification of the lowest price found and the purchase link, if the price found is 20% or more off the original price. 

### Additional:

- We can put this program to run every 4 hours or every day at 10:00 in the morning. We can do this via the Windows task scheduler or leave the code running in the background with a time.sleep(time)
- If you want, you can leave the browser without appearing at the end of your code, to make your program more subtle