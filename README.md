
# Tripal Crop Docker

This docker container contains all the Drupal, Tripal and DivSeek Canada extension modules you need to create your own Tripal Crop site. Furthermore, it contains a number of command-line drush commands to make maitenance and administration of your Tripal crop site more streamlined.

## Under Development: The Plan

- Docker image should be generic for all crops.
   - Download all the code for the modules but do not install them.
   - Do not create the database and install the site
- create command-line bash commands for wasy site management
   - Initial setup: creates database, installs site, and runs drush commands
   - Certbot: create/renew certificate
   - Upgrade? upgrades drupal and all extension modules
- create a tripal extension module with drush commands
   - install and configure defaults for all Modules
   - add permissions and roles which make sense

## Funding

The first iteration of the platform is funded under a [Genome Canada Project](https://www.genomecanada.ca/en/divseek-canada-harnessing-genomics-accelerate-crop-improvement-canada) with co-funding from other partners.

## Citation

Lacey-Anne Sanderson, Kirstin E. Bett, Loren H. Rieseberg (2020) Tripal Crop Docker: A fully provisioned Tripal site aimed at supporting crop-focused and breeding research. DEVELOPMENT VERSION. DivSeek Canada Pilot Project: Harnessing Genomics to Accelerate Crop Improvement in Canada.
