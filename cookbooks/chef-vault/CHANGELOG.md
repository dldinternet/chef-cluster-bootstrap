chef-vault
==========

v1.2.1 (2015-02-17)
-------------------
- Being explicit about usage of the chef_gem's compile_time property.
- Eliminating future deprecation warnings in Chef 12.1.0.

v1.2.0 (2015-02-04)
-------------------

- COOK-4672: Make the library helper into a module instead of adding into Chef::Recipe
- Prevent variable masking
- Fix inverted existence check for `current_resource`

v1.1.5 (2014-09-25)
-------------------
- Adding ChefVault::Exceptions::SecretDecryption exception handling

v1.1.4 (2014-09-12)
-------------------

- Fix loading of current resource in `chef_vault_secret` (Nathan Huff)
- Allow `chef_vault_item` to fall back to plain data bags
- Set default version of `chef-vault` gem to one required by libraries

v1.1.2 (2014-06-02)
-------------------

### Bug
- **[COOK-4591](https://tickets.opscode.com/browse/COOK-4591)** - resource to create chef-vault-encrypted-items in recipes


v1.1.0 (2014-06-02)
-------------------

- [COOK-4591]: add a resource to create chef-vault-encrypted-items in recipes

v1.0.4 (2014-01-14)
-------------------

- Provide an fallback to regular data bag item loading when a "development mode" attribute is set.

v1.0.2 (2013-09-10)
-------------------

- Add Chef::Recipe helper method (`chef_vault_item`)

v1.0.0 (2013-09-10)
-------------------

- Initial Release
