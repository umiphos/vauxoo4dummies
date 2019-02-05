Migration from 11.0--->>>12.0
==============================

product_uom does not exist anymore, it was replaced by uom, and now it has it's own module in **addons**
from the model account_move, the method post now receives another value, invoice, and yes, it's the invoice of that move
there is no more service_cost_01, not its named: product_product_1, check the category, this info can be fount in this commit https://github.com/odoo/odoo/commit/bed29a4aeab0ec6ef0c02975ee86655d6a030299#diff-02b7568ee4219d629aa27a59bda1c869


