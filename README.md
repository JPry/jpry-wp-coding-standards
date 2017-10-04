# JPry WP Coding Standards

Customized set of coding stanardards for WordPress.

This ruleset includes the following standards from the main [WordPress Coding Standards](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards#rulesets) repository:

* WordPress-Core
* WordPress-Docs
* WordPress-Extra 

It includes the following modifications:

* WordPress file naming conventions are ignored (`WordPress.Files.FileName` sniff). This allows for modern naming standards that specify the class name as the file name.
* The `create_function` and `obfuscation` groups from the `WordPress.PHP.DiscouragedPHPFunctions` sniff are ignored. This is in line with the normal WordPress rules.
