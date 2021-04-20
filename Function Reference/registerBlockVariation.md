# registerBlockVariations

## Description
Registers a block variation e.g. social icons different types.

## Fields

**[name]**

**[title]**
* _(string)_
* _(Required)_ 
* _description_ The Variation Title 
* _Defult value:_ null

[description]
* _(string)_ The Variation Description
* Default value: 

[category] 
* _(string)_
* _optional_ 
* _descripition_ A category classification, used in search interfaces to arrange block types by category.

[icon]

[isDefault]

[attributes]

[innerBlocks]

[example]

[scope]

[keywords]

[isActive]

[providerNameSlug]

## Source

File: `packages/block-library/src/index.native.js`

[View on Github](https://github.com)

## Related

## Changelog

## Example

```javascript
wp.blocks.registerBlockVariation( 'core/embed', {
    name: 'custom',
    attributes: { providerNameSlug: 'custom' },
} );
```