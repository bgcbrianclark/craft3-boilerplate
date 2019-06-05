# Craft CMS 3 Page Structure Boilerplate

- Copy all files and Root folders to project root:

  - gulpfile.js

  - package-lock.json

  - package.json

  - /source

- Remove /templates/index.php, replace with everything in /templates folder.

- Add folders within local /web to project /web folder.

- Update .gitignore to add /source and development files to ignore.

### Add Common Plugins from CLI (from project root)

- [Contact Form](https://github.com/craftcms/contact-form)  
  `composer require craftcms/contact-form`
  `./craft install/plugin contact-form`

- [Contact Form Extensions](https://github.com/riasvdv/craft-contact-form-extensions/blob/master/README.md)  
  `composer require rias/craft-contact-form-extensions`
  `./craft install/plugin contact-form-extensions`

- [SEO](https://github.com/ethercreative/seo)  
  `composer require ether/seo`  
  `./craft install/plugin seo`

- [Redactor](https://github.com/craftcms/redactor)  
  `composer require craftcms/redactor`  
  `./craft install/plugin redactor`

- [Typed Link Field](https://github.com/sebastian-lenz/craft-linkfield)  
  `composer require sebastianlenz/linkfield`  
  `./craft install/plugin redactor`

- [Super table](https://github.com/verbb/super-table)  
  `composer require verbb/super-table`  
  `./craft install/plugin super-table`
