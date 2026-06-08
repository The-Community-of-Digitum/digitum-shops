# 🏪 Shop Format

Every shop must follow this structure:

```shop
Shop Name: <Name>
Owner: <Citizen Name>
Category: <Category>
Description:
<What the shop sells>

Items:

Name: <Item Name>
Price: <D$ Amount>
Description: <What it is>
Type: <Recipe / Craft / Idea / Program / PCG / Service>
```

Shops must be fair, creative, and non-exploitative.

# 💸 Purchase Process (PR-Based)

To buy something from a shop:

1. The buyer creates a Pull Request in this repo.
2. The PR includes:
   - item name
   - shop name
   - price
   - link to the item listing
   - confirmation that they agree to pay

3. The shop owner reviews the PR.
4. If approved:
   - the shop owner updates `balances.json` in the ledger repo
   - the shop owner adds a line to `purchases.log`
   - the buyer receives the item

This ensures transparency and prevents scams.

# 🗂️ Shop Categories

Digitum recognizes the following shop types:

- Recipe Shops
- Craft Shops
- Idea Shops
- Program Shops
- PCG Shops
- Service Shops
- Mixed Shops
- Specialty Shops (e.g., Breakfast Guild shops)

New categories may be added through PR.
