# QR Capitalist product table (v2)

The barcode → category table bundled with the game QR Capitalist, released under the Open Database License because
it is derived from the Open Food Facts family of databases.

- `products.csv`: 343,665 rows of `code,category`. A code is a 13-digit GTIN (UPC-A codes are
  zero-padded) or an 8-digit EAN-8. A category is one of: pantry, produce, dairy, meat, frozen, beverages, snacks, bakery, household, pet, beauty, books, paper.
- Table version 2, built 2026-10-21 from the bulk exports of Open Food Facts, Open Beauty Facts, Open Pet
  Food Facts and Open Products Facts, keeping US products with category tags and mapping each product's category tags
  to the game's categories (first matching rule wins). 1 further codes come from the game's small hand-made seed
  list. No product names, brands, images or any other fields are included.

## Licence and attribution

This database is made available under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Its contents are under the [Database Contents License (DbCL) 1.0](https://opendatacommons.org/licenses/dbcl/1-0/).

Derived from: [Open Food Facts](https://world.openfoodfacts.org), [Open Beauty Facts](https://world.openbeautyfacts.org),
[Open Pet Food Facts](https://world.openpetfoodfacts.org) and [Open Products Facts](https://world.openproductsfacts.org),
© their contributors, under the ODbL.

If you use this table publicly, the ODbL asks you to attribute it, and to share any database you derive from it
under the same licence.
