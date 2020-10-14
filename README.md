# AEM-STUDIO

An AEM VS CODE snippet extension for frontend development.
[Learn more about VS Code snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets)


## Features

- Quickly generate/scaffold AEM snippets
- Work in progress (WIP)

### Snippets usage/triggers

- `aem_dialog` a dialog settings into `_cq_dialog/.content.xml` file
- `aem_dialog_field` inserts a dialog field into `_cq_dialog/.content.xml` into the items node
- `aem_htmlTag` insert a dialog field into the `_cq_htmlTags/.content.xml` file
- `aem_component` insert component into your `/.component.xml` file
- `aem_component_advanced` insert component with `sling:resourceSuperType` field into your `/.component.xml` file
- `mvn_archetype` Generates the code/commands for generating an AEM  Maven archetype project in batch mode command(s)


### Development

- Clone this repo
- Install Microsoft VSCE `npm install -g vsce` [exension manager](https://www.npmjs.com/package/vsce)
- Install Auto Changelog `npm install -g auto-changelog` [Auto Changelog](https://www.npmjs.com/package/auto-changelog)
- Install np `npm install --global np` [np](https://www.npmjs.com/package/np)
- Build extension `npm run build`
- `npm run history` to generate changelogs

### Contributing

If you would like to contribute to this extension

- Clone the repo `git clone https://github.com/shawn-sandy/aem-fe-studio`
- Add an extension to the `package.json` fix a bug/typo etc
- Add snippets to `snippets.code-snippets` file
- Submit a Pull request
- Approval subject to review

### Issues

I you find any errors, bugs, typos, would like to recommend an extension, etc. Please open an issue here https://github.com/shawn-sandy/codestudio/issues

### License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**Enjoy!**
