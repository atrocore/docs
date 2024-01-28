# First steps - how to configure the system correctly?

In order for the product data to be qualitative, the main entities used in the system must be properly configured prior to starting system use. The term “entity” is used for modules or tables of structured data that are stored in the system with a specific purpose. So, the categories, channels, associations, catalogs, etc. count as entities. The entities can be linked to one another, for example a product can belong to several categories at the same time.

The user does not necessarily have to use all available entities. If he does not need some entities, these can simply be deactivated, and vice versa, if further entities are required, these can also be created and linked to existing entities.

In this article we assume the requirements of an average user who needs all entities. In the following we will explain which entities should be configured for the full and effective system work.

## Configure attributes

A product attribute determines a certain property of a product. Thanks to the typing of the attributes, their values are also typed. The product attributes are not only used to describe the product in full, but also for the filters to help the end customer to find the required product more quickly. This is precisely why the product description with the attributes is very important. Typical attributes for clothing are, for example, size and color.

AtroPIM has 14 attribute types. The use of attribute types is necessary for better typing and corresponding validation of the data in the system. For more information on attributes and their types, please read the [documentation](../user-guide/attributes.md).

For more information on configuring the product attributes, read the article:  [“How to create the product attributes?”](./how-to-create-the-product-attributes.md).

## Configure associations 

Associations are used to store various relationships between the products. Such relationships may appear interesting to potential customers for a variety of reasons - one may want to buy a replacement for an existing product, another may be interested in certain associated products, etc. Associations can be both one-sided (product A is associated with product B, but not the other way around ) as well as bilateral (if product A is associated with product B, then product B is also associated with product A).

With AtroPIM each user can configure the relationship types he intends to use himself. The following types of relationships are pre-configured:

- Replaces
- Is replacement of
- Cross-selling
- Up-selling
- Consist of
- Is part of
- etc.

For more information on creating product associations, read the article: [“How to create a full and qualitative product description in 6 steps.”](./product-description-in-6-steps.md#step-5-enter-associated-products).

## Configure product families

The definition of a product family is the first step in segmenting the user's product range. You need product families in order to unify the descriptions of the products of the same nature. Product families determine which attributes a product from this product family should have.

For more information on the configuration of the product families, read the article: [“How to create the product families?” ](./how-to-create-the-product-families.md).

## Configure categories

Categories are used to group the products for marketing purposes. The categories help end customers to find the desired product more quickly. The categories are used in almost every online store and on every market place. By assigning a category to a parent category, the categories can form category trees. You can create more than one category tree in AtroPIM. Each product can be assigned to one or more categories.

The biggest difference between categories and product families is that a product can have multiple categories, but only one product family. The product family determines which product attributes have to be filled in for a product so that the product description is considered qualitative. A category, on the other hand, is only used for marketing purposes - the product should be found faster and easier by a customer.

By assigning a product to a certain category, the channel to which the product data is to be transferred can also be determined.

For more information on product categorization, read the article: [“How to configure the categories?”](./how-to-configure-the-categories.md). 

## Configure catalogs and channels

Catalogs can be used in the system to manage different product ranges, catalogs from different suppliers or different versions of your own catalogs. A master catalog can be created by merging the data from other catalogs.

Channels are the destinations for product information; these can be, for example: creation of a print catalog, online stores, marketplaces, etc. The use of the channels enables an effective implementation of your multichannel or omni-channel strategy.

For more information on the configuration of the product families, read the article: [“How to use the catalogs and channels correctly?”](./how-to-use-the-catalogs-and-channels.md). 
