#Reference Composer Project Implementation

This is for work on Drupal cor eauto-updates.

Based on Symfony 3.4.11 (corresponding to Drupal 8.5.6)

ran this:

composer create-project symfony/framework-standard-edition fakedrupal-reference "3.4.11"

Then look at the locked external dependencies from 8.5.6
https://github.com/webflo/drupal-core-strict/blob/e95610956f961f4421fd9a36849dcd6e2b55f4fe/composer.json

Require each of those exact versions except "wikimedia/composer-merge-plugin" and "composer/installers"

