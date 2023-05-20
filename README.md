Clone this project.

Note: If you have not set up with Magento Cloud 2.3.* locally before - initially use a composer.json file with just "magento/magento-cloud-metapackage": ">=2.3.5 <2.3.6", in repositories section and install an empty DB using CLI. THis is to check you are able to install Magento default locally.

1. Run: composer install
2. Request access to Cloud Portal for project (contributor level is sufficient). Use magento-cloud cli to obtain Master DB copy from server. Install locally (Via Docker container if needed)
3. Add env.php file (standard)
4. Run bin/magento set:up
