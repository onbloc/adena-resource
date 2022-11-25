
# Adena Resource

This repository contains a comprehensive list of tokens and chains supported on Adena.

If you wish to register your token data to get it displayed it on Adena's products, please submit a PR that adheres to the Token Registration Guidelines below.

## Token Registration Guidelines

Follow the steps in order to add a token to this list.

1.  Fork the repository to your own GitHub account.
2.  Clone the project to your device.
3.  Create a branch locally with a succinct but descriptive name.
4.  Commit changes to the branch that includes the following:

	- A 16x16 Token Image in **token_symbol.svg** format (ex: **gnot.svg**) in the [/images/token](https://github.com/onbloc/adena-resource/tree/main/images/token) folder.
	- An entry in the `tokens.json` file that matches the following format 👇

```jsonc
string: {
	//token symbol in capital letters (ex: GNOT)
	"type": string,
	//token name (ex: Gnoland)
	"name": string,
	//whole denomination of the token (ex: gnot)
	"denom": string,
	//unit of denom
	"unit": number,
	//minimal denomination of the token (ex: ugnot)
	"minimalDenom": string,
	//unit of minimalDenom
	"minimalUnit": number,
	//link that points to the svg file of your logo
	"image": string
	//**REMOVE ALL COMMENTS BEFORE THE ACTUAL PR**
}
```
5.  Push changes to your fork.
6.  Open a PR in our repository and wait for us to review and pull your changes.

Our members will review your submission and accept your PR ONLY if it follows the correct format.

Although we're managing this list for Adena's prodcuts, we welcome anyone in the community to use resources provided on this repository to display logos & symbols of tokens or RPC/API Endpoints for chains on your dapps, lists, data aggregators, or any where applicable.

## Disclaimer
The Adena Team ("we") allows anyone to submit information about any tokens.

Although we throughly review the submissions, we do not gurantee the integrity of tokens on this list.

The approval of a submission is not an endorsement or nor an investment advice of the asset.

In no event shall the Adena Team be liable for your damages resulting from investments in assets included in this repository.

The Adena Team reserves the right to reject or remove token submissions at any time at our sole discretion.
