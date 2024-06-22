### Demo repo for PHPStorm support

PHP > Quality Tools > PHP CS Fixer
- Toggle ON
- System PHP (I have PHP 8.3 on my machine)
- Ruleset: Custom, path to .php-cs-fixer.php in this repo

Running Inspect Code on `config/app.php` returns no errors other than "Laravel's" not being in the spelling dictionary.

Running `vendor/bin/php-cs-fixer check config/app.php -v` in the terminal returns errors:

`declare_strict_types, blank_line_after_opening_tag, no_extra_blank_lines`
