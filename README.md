# Accumulate Token Registry
You can use this repository to add your token on the Accumulate into the registry.
Tokens, that added into the registry:
- Displayed in the `Tokens` section of Accumulate Explorer
- Searchable by token symbol in the explorer and wallets

## How to add your token
1. Fork this repository
2. Copy `ACME` folder and rename it to your token symbol
3. Update logo image (256×256px, JPG/PNG) and `token.json`
4. Create pull request

## Important
`token.json` syntax:
- `tokenIssuer` should start with `acc://`
- `logo` should point to the image into this github repo
- `url` should start with `https://`
