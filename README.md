#Reference Composer Project Implementation

This is for work on Drupal cor eauto-updates.

Based on Symfony 3.4.11 (corresponding to Drupal 8.5.5)

ran this:

composer create-project symfony/framework-standard-edition fakedrupal-reference "3.4.11"

Then look at the locked external dependencies from 8.5.5
https://github.com/webflo/drupal-core-strict/blob/a3eaee3a20cf87e956ee925e1ea564f16e768129/composer.json

Require each of those exact versions except "wikimedia/composer-merge-plugin" and "composer/installers"

