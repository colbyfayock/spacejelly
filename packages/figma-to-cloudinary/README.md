# Figma to Cloudinary

Transform a Figma artboard into a Cloudinary URL!

**This is super experimental and is not officially supported by Cloudinary**

## Getting Started

1. Install dependencies

```shell
yarn add @spacejelly/figma-to-cloudinary
# or
npm install @spacejelly/figma-to-cloudinary
```

2. Import dependencies

```js
const { figmaToCloudinary } = require('@spacejelly/figma-to-cloudinary');
```

3. Configure and run script!

```js
await figmaToCloudinary({
  cldCloudId: 'your-cloudinary-cloud-name',
  cldImageId: 'your-cloudinary-image-id',
  figmaFileId: 'figma-file-id',
  figmaNodeId: 'figma-node-id',
  textFields: {
    FIGMA_TEXT_FIELD_NAME: 'Text'
  }
});
```