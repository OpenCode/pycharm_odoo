# Pycharm for OpenERP/Odoo

Set of plugins, snippets and templates to transform PyCharm in a perfect tool for OpenERP/Odoo developers

Search information on Twitter with tag \#PyCharmOdoo: https://twitter.com/search?f=tweets&q=%23PyCharmOdoo&src=typd

## Snippets

### Import

* Clone the repo
* Open PyCharm
* Go to File -> Import Settings... and load the file snippets.jar from cloned path

### List of snippets

Go to File -> Settings -> Editor -> Code Style -> Live Templates and read snippets list in group Odoo Code, Odoo View, OpenERP Code and ErpPeek

Complete List:

#### Python

* pdb

#### OpenERP Code

* bool openerp
* binary openerp
* browse openerp
* char openerp
* class openerp 7
* class openerp 6
* class inherit openerp 6
* class inherit openerp 7
* create openerp
* date openerp
* datetime openerp
* pool
* float openerp
* import openerp 6
* import openerp 7
* int openerp
* m2m openerp
* m2o openerp
* o2m openerp
* raise openerp 6
* raise openerp 7
* search openerp
* selection openerp
* columns openerp

#### Odoo Code

* @api odoo
* binary odoo
* char odoo
* class odoo
* class_in odoo
* compute odoo
* date odoo
* datetime odoo
* def
* float odoo
* import odoo
* int odoo
* m2m odoo
* m2o odoo
* o2m odoo
* raise odoo
* selection odoo
* text odoo
* html odoo
* ref odoo
* env odoo
* search odoo
* create odoo
* browse odoo
* bool odoo
* create definition odoo
* write definition odoo
* on_change odoo
* dp odoo
* name_search odoo
* name_get odoo
* warning import odoo
* unlink definition odoo
* default date odoo

#### Odoo XML


* action
* attribute
* button
* chatter
* field
* filter
* form
* groupby
* inherit
* label
* menuitem
* notebook
* odoo
* page
* report
* statusbar
* tree
* widget
* xml
* xpart

#### ErpPeek

* client erppeek
* search erppeek
* count erppeek

### Use

In python or XML file write the snippet and press tab button to insert the complete code

## Templates

### Import

* Clone the repo
* Open PyCharm
* Go to File -> Import Settings... and load the file file_template.jar from cloned path

### Use

Go to menu File -> New and select the right template. Insert your informations.

#### OpenERP - Odoo Manifest

File Name:

    Required.
    It must be "\_\_openerp\_\_"

Version:

    Not required.
    OpenERP/Odoo version. It must be 6, 7, 8 or 9

Category:

    Not required.
    Module category
    Example: Sale

Website:

    Not required
    Author website
    Example: https://github.com/OpenCode/pycharm_odoo

Depends:

    Not required
    List of depends (other odoo modules) separated by comma
    Example: sale,account,mrp,stock
