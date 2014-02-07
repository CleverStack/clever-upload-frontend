# Cleverstack File Upload module

Provides file uploading frontend components to CleverStack's ecosystem

## Setup

### Setting up Bower components
1. Add `filepicker` to your bower.json.

2. run `bower install`

3. Add datatables and moment to your app/modules/main.js file.
 - Add the paths to the filepicker plugins to the paths object.
 - A shim needs to be added to the shim object for filepicker
 - Lastly, filepicker needs to be added to the required array at the bottom.

4. Add `filepicker` to your app/modules/application/main.js file. It belongs in the array of required modules.

### Setting up Cleverstack Fileupload
1. Add 'cs_file_upload' to your app/modules/main.js file.
It belongs in the `package` array at the top.

2. Add `cs_file_upload` to your app/modules/application/main.js file.
It belongs in the array of required modules.

3. Add `cs_file_upload` to your app/modules/application/module.js file.
`cs_datatables` belongs in your `app` module's array of required modules.

## Usage
1. Add the `filepicker` angular module to your controller.
