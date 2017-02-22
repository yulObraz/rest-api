Known Issues
============

Irregularly Typed Fields
------------------------

Some fields may not behave as expected when used in the query syntax due to their types being incorrect. Unfortunately, this isn't a problem with the API itself, but instead with the underlying data.

The fields that have been identified with this issue so far are as follows:

* [shipping_providers](resources/shipping_providers.md)
	* `markup_amount`
* [users](resources/users.md)
	* `last_login_attempt_at`
	* `last_login_at`

Bugs (Features)
---------------
* [custom_fields](resources/custom_fields.md)
	* does not return category's custom fields

* [webhook](webhooks.md)
	* GetProductStatus does not update status on product page. It makes request but does not show result. 
	* GetProductStatus: Requests are cached. So you can set new inventory and see it in admin but you will get old inventories quantity in request.
