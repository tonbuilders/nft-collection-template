# TON Minter template

This is a template to create your first NFT collection in TON blockchain with [TON Minter](https://github.com/tonbuilders/tonbuilders-minter).

Original template is [here](https://github.com/tonbuilders/nft-collection-template).

## How to use

[SEE THE VIDEO TUTORIAL](https://youtu.be/X-_X-_X-_X)

or

To use this template, you need to:
1. Click "Use this template"
2. Create own repository from template
3. Customize your collection
   1. Change images in `/images` folder
   2. Commit changes to your repository
   3. Change `collection.json` data
      1.  Paste link to your images by "raw" GitHub links
   4. Change NFT configs in `/nft` folder
      1. Do the same you did in `collection.json`
4. Open [TON Minter](https://github.com/tonbuilders/tonbuilders-minter) and connect TON Wallet
5. Setup collection
   1. Paste link to `collection.json` in Minter
   2. Paste link to folder with NFT `.json` files in Minter
   3. Write royalties in Minter
6. Setup first NFT
   1. Write unique index (start from `0`)
   2. Paste link to `nft.json` from your repository in Minter
7. See the result in TON Explorer 🚀