# MantaSails README

[![made in nigeria](https://img.shields.io/badge/made%20in-nigeria-008751.svg?style=for-the-badge)](https://github.com/acekyd/made-in-nigeria) [![SailsJs](https://img.shields.io/badge/Framework-SailsJs-blue.svg?longCache=true&style=for-the-badge)](https://sailsjs.com/)

MantaSails is a Sails snippet tool for vscode. It is efficient and fun to make use of. It enables a faster workflow for devs using Sails. It has been tested and I am sure it would help become more productive.

> Tip: After selecting what snippet to use, use the tab key to navigate inputs.

---

## Table of Contents
- [Installation](#installation)
- [License](#license)
- [List of snippets](#list-of-snippets)
- [Contributions](#contributions)
- [Task List](#task-list)
- [Contributors](#contributors)

## Installation
1. Open the **Extensions** sidebar in VS Code. `View → Extensions`
2. Search for `MantaSails`, choose "MantaSails"
3. Click **Install** to install it

---
## License

MantaSails is released under the [MIT License](https://github.com/lennyAiko/MantaSails/blob/main/LICENSE)

---
## List of snippets
|Prefix       |Code                       |
|---          |---                        |
|mxf or fhelper|generate a function|
|si or sinput|generate an input template|
|ei or einput|generate an exit template|
|gr or getroute|generate a get route template|
|pr or postroute|generate a post route template|
|pur or putroute|generate a put route template|
|par or patchroute|generate a patch route template|
|battr or booleanattribute|generate a boolean attribute template|
|sattr or stringattribute|generate a string attribute template|
|nattr or numberattribute|generate a number attribute template|
|rb or rbody|generate a template to unpack request|
|atc or addtocollection|generate a template for `.addToCollection`|
|arc or archive|generate a template for `.archive`|
|aarc or accessarchive|generate a template for `.Archive.findOne`|
|avg or average|generate a template for `.average`|
|cnt or count|generate a template for `.count`|
|co or createobj|generate a template for `.create`|
|cof or createobjfetch|generate a template for fetch `.create`|
|cb or createbulk|generate a template for `.createEach`|
|cbf or createbulkfetch|generate a template for fetch `.createEach`|
|drs or deleterecords|generate a template multiple `.destroy`|
|dsr or deletespecificrecords|generate a template for specific `.destroy`|
|drr or deleterangerecords|generate a template for range `.destroy`|
|dr or deleterecord|generate a template for `.destroy`|
|fo or findOne|generate a template for `.findOne`|
|f or find|generate a template for `.find`|
|fop or findproj|generate a template for projective `.find`|
|foc or findorcreate|generate a template for `.findOrCreate`|
|foce or findorcreateexec|generate a template for `.findOrCreate`|
|rc or removecollection|generate a template for `.removeFromCollection`|
|rsc or replacecollection|generate a template for `.replaceCollection`|
|sr or streamrecords|generate a template for `.stream`|
|sumr or sumrecords|generate a template for `.sum`|
|urs or updaterecords|generate a template for multiple `.update`|
|ursf or updaterecordsfetch|generate a template for fetch `.update`|
|ur or updaterecord|generate a template for `.updateOne`|
|vr or validaterecord|generate a template for `.validate`|

---
## Contributions

1. Fork
2. Update `snippets.code-snippets` following the standard
3. Make PullRequest
4. Be happy and go for a beer or coffee.

Created by **[Lennox Charles](https://github.com/lennyaiko)**.
Go follow on **[Twitter](https://twitter.com/c_lennyx)**!

---
## Task List
- [ ] Work on attributes for associations: Create snippets for associations
- [ ] Fix default in [`sinput`, `si`]: Change from `default` to `defaultsTo`
- [ ] Add validations to attributes: for example, email should be `sattre` and cross-check others to be validated
- [ ] Fix `createEach`: Objects should be in an array
- [ ] Update readme: check completed tasks and add contributors

## Contributors
- Oladapo Ayodeji (@Dipsaint1)
- Lennox Charles (lennyAiko) 


**Enjoy!**
