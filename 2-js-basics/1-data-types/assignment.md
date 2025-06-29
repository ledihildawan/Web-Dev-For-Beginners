# Data Types Practice

## Instructions

Imagine you are building a shopping cart. Write some documentation on the data types that you would need to complete your shopping experience. How did you arrive at your choices?

## Rubric

| Criteria | Exemplary                                                                   | Adequate                    | Needs Improvement           |
| -------- | --------------------------------------------------------------------------- | --------------------------- | --------------------------- |
|          | The six data types are listed and explored in detail, documenting their use | Four datatypes are explored | Two data types are explored |

## [Shopping Cart Data Types](https://chatgpt.com/share/68613200-3ad4-8013-baa3-13219b70c230)

### String
- **Usage:** Names of products, descriptions, categories, and user messages.
- **Example:**
  ```js
  let productName = "Organic Green Tea";
  let category = "Beverages";
  ```
- **Why?** Strings are ideal for representing textual data and labels essential for user interface display and search functionality.
  
### Number
- **Usage:** Prices, quantities, discounts, tax rates, and total amounts.
- **Example:**
  ```js
  let price = 59.99;
  let quantity = 3;
  let discountRate = 0.15;
  ```
- **Why?** Shopping involves a lot of arithmetic calculations; numbers make it possible to compute subtotals, taxes, and final totals.

### Boolean
- **Usage:** To check conditions like whether a coupon is applied, an item is in stock, or a user is logged in.
- **Example:**
  ```js
  let isInStock = true;
  let isCouponApplied = false;
  ```
- **Why?** Booleans are perfect for controlling flow and enabling conditional features like promotions or checkout availability.