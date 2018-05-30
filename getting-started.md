# Getting Started

## Introduction

This documentation provides a list of the features available within the GDPR module for Drupal 7 and 8 and a guide for using them. We hope that this guide will help you to get started using GDPR in your Drupal 7 or Drupal 8 project today.

## Installation

### Install GDPR Modules using Composer

The GDPR module can be found in Drupals projects. To install using composer, run the following command:

```bash
composer require drupal/modulename
```

from the webroot directory, not inside the core directory, to install the module with all it's Composer dependencies.

### Installing GDPR modules using the command line

In addition to installing modules using the UI and [composer](getting-started.md#install-gdpr-modules-using-composer), you may also download and install modules from the command line:

* The recommended way to download modules is with Composer. However, you may still use Drush 8 or Drupal Console to download the modules, but it does not adjust your composer.json file.
* Both Drush and Drupal Console will install modules for you. \(In Drupal 8 installing and enabling a module is the same.\)

Downloading and installing modules from the command lines is the fastest way to extend your installation.

#### Drush

To install a module using Drush, execute the command below:

```text
drush en gdpr
```

With Drush 8 you can download a module using:

```text
drush dl gdpr
```

#### Drupal Console

To install a module with Drupal console, execute the command below:

```text
drupal moi gdpr
```

With Drupal Console you can download a module using:

```text
drupal mod gdpr
```

## Dependencies

Various submodules are required for the GDPR module:

* **gdpr** \(main\): [Checklist API](https://www.drupal.org/project/checklistapi)
* **gdpr\_consent:** [Token](https://www.drupal.org/project/token), [Message](https://www.drupal.org/project/message), [Entity Reference Revisions](https://www.drupal.org/project/entity_reference_revisions)
* **gdpr\_fields:** [Ctools](https://www.drupal.org/project/ctools)
* **gdpr\_dump:** [Hidden author](https://www.drupal.org/project/anonymizer) \(aka. Anonymizer\)



