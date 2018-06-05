# npm-versioning-test
NPM versioning test repo

### NPM publish package

	npm login
	
##### Output:

    Username: _USERNAME_
    Password: 
    Email: (this IS public) _USEREMAIL_
    Logged in as _USERNAME_ on https://registry.npmjs.org/.

##### Publish:

	npm publish --access public

### NPM release package

https://docs.npmjs.com/cli/version

##### Custom suffix

	npm version 2.0.0-beta.0
	2.0.0-1 -> 2.0.0-beta.0

##### Patch:

	npm version patch
	0.0.1 -> 0.0.2

##### Minor:

	npm version minor
	0.0.2 -> 0.1.0

##### Major:

	npm version major
	0.1.0 -> 1.0.0

#### Pre-Versions

##### Prepatch:

	npm version prepatch
	1.0.0 -> 1.0.1-0

##### Preminor:

	npm version preminor
	1.0.1-0 -> 1.1.0-0

##### Premajor:

	npm version premajor
	1.1.0-0 -> 2.0.0-0

##### Prerelease

	npm version prerelease
	2.0.0-0 -> 2.0.0-1
