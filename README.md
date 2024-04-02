# EBoost - Custom layout Update XML (For developer)

This simple module adds a new layout update xml for handler, allowing you to update layout xml without update code.

## Installation

Require the module

```bash
composer require eboosttech/magento2-layoutupdate
```

Enable the module

```bash
php bin/magento module:enable EBoost_LayoutUpdate
```

Run setup to install module and set up table(s)

```bash
php bin/magento setup:upgrade
```

## Usage

After installed, you can go to `Eboost > Custom Layout Update XML` then click `Add new` to create XML layout

![Layout Update XML Menu Screenshot](docs/xml-layout-menu.png)
![Layout Update XML Add New Button Screenshot](docs/xml-layout-add-new-button.png)

Then input data for the form

![Layout Update XML Add New Form Screenshot](docs/xml-layout-add-new-form.png)

save and clear cache, then go to frontend page to see result

## How to detect handle for a page


## Bugs/Feature Requests & Contribution

Please do open a pull request on GitHub should you want to contribute, or create an issue.

## License
[BSD-4-Clause](http://directory.fsf.org/wiki/License:BSD_4Clause) - Do as you wish 👍