framework
=========

A framework using PHP.

*Goal: Creating a flexible framework in PHP.*

Planning
--------
- v0.1: A basic file structure
- v0.2: First page with Smarty
- v0.3: First page using a DB manager
- v0.4: Using javascript plugins
- v0.5: Controller based plugin versioning

File structure
--------------
- configs
  - db_config.php
- defaults
  - DefaultsBaseController.php (Base for all controllers)
  - default (default project)
    - DefaultBaseController.php (Base controller for default project)
- pages
  - default (default project)
    - home (page 'home')
      - HomeController.php
      - home.js (javascript for home)
      - home.css
      - read.js (javascript for reading home)
- plugins
