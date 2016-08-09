# Pycharm for OpenERP/Odoo

Set of plugins, snippets and templates to transform PyCharm in a perfect tool for OpenERP/Odoo developers

## Snippets

### Import

* Clone the repo
* Open PyCharm
* Go to File -> Import Settings... and load the file snippets.jar from cloned path

### List of snippets

Go to File -> Settings -> Editor -> Code Style -> Live Templates and read snippets list in group Odoo Code, Odoo View, OpenERP Code and ErpPeek

### Use

In python or XML file write the snippet code and press TAB to insert the complete code

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
