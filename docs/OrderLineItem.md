# SquareConnect::OrderLineItem

### Description

Represents a line item in an order. Each line item describes a different product to purchase, with its own quantity and price details.

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** | The name of the line item. | [optional] 
**quantity** | **String** | The quantity purchased, as a string representation of a number. | 
**note** | **String** | The note of the line item. | [optional] 
**catalog_object_id** | **String** | The [CatalogItemVariation](#type-catalogitemvariation) id applied to this line item. | [optional] 
**variation_name** | **String** | The name of the variation applied to this line item. | [optional] 
**modifiers** | [**Array&lt;OrderLineItemModifier&gt;**](OrderLineItemModifier.md) | The [CatalogModifier](#type-catalogmodifier)s applied to this line item. | [optional] 
**taxes** | [**Array&lt;OrderLineItemTax&gt;**](OrderLineItemTax.md) | The taxes applied to this line item. | [optional] 
**discounts** | [**Array&lt;OrderLineItemDiscount&gt;**](OrderLineItemDiscount.md) | The discounts applied to this line item. | [optional] 
**base_price_money** | [**Money**](Money.md) | The base price for a single unit of the line item. | [optional] 
**gross_sales_money** | [**Money**](Money.md) | The gross sales amount of money calculated as (item base price + modifiers price) * quantity. | [optional] 
**total_tax_money** | [**Money**](Money.md) | The total tax amount of money to collect for the line item. | [optional] 
**total_discount_money** | [**Money**](Money.md) | The total discount amount of money to collect for the line item. | [optional] 
**total_money** | [**Money**](Money.md) | The total amount of money to collect for this line item. | [optional] 


