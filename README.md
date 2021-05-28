# PythonEcommerce
## Objects

- Users
- Stores
- Products
- ProductOptions
- Options
- ProductPhotos
- ProductCategories
- Photos
- Categories
- Wishlists
- WishlistProducts
- Discounts
- Orders
- Payments
- Carts

## Information

- Users:
  - Id
  - Name
  - Age
  - Sex
  - Country
  - PostalCode
  - City
  - State
  - Address
- Stores: 
  - Id
  - Name
  - CustomUrl
- Products:
  - Id
  - Name
  - SKU
  - Price
  - QtyStock
  - ShortDescription
  - LongDescription
  - StoreId
- ProductOptions:
  - Id
  - OptionId
  - ProductId
- Options:
  - Id
  - Name
  - QtyStock
  - Description
  - PhotoId
- ProductPhotos:
  - Id
  - PhotoId
  - ProductId
- ProductCategories:
  - Id
  - ProductId
  - CategoryId
- Photos:
  - Id
  - Url
- Categories:
  - Id
  - Name
  - Description
- Wishlists:
  - Id
  - Name
  - Total
  - UserId
- WishlistProducts:
  - Id
  - WishlistId
  - ProductId
- Discounts:
- Orders:
- Payments:
- Carts:

## Main Functions

- Users:
  - Login
  - Register
  - RememberPassword
  - GetAccountInformation
  - UpdateAccountInformation
  - DeleteAccount

- Stores:
  - CreateStore
  - GetStoreInformation
  - UpdateStoreInformation

- Products:
  - CreateProduct
  - GetProduct
  - UpdateProduct
  - DeleteProduct

- ProductOptions:
  - CreateProductOption
  - DeleteProductOption
  - GetProductOption
  - UpdateProductOption

- Categories:
  - CreateCategory
  - UpdateCategory
  - GetCategory
  - DeleteCategory

- Wishlists:
  - CreateWishlist
  - UpdateWishlist
  - GetWishlist
  - DeleteWishlist

- Discounts:
  - CreateDiscount
  - UpdateDiscount
  - GetDiscount
  - DeleteDiscount