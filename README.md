
# Adena Resource

This repository contains a comprehensive list of tokens and apps supported on Adena.

Adena will fetch the data on this repo to display tokens on the Wallet & History menu, and apps on the Explore menu.

If you wish to register your project on this list, please submit a PR that adheres to the Project Registration Guidelines below.

## Project Registration Guidelines

Follow the steps in order to add a project to this list.

1.  Fork the repository to your own GitHub account.
2.  Clone the project to your device.
3.  Create a branch locally with a clear, descriptive name.
4.  Commit changes to the branch that includes the following:
	- Tokens
		- A 120x120 token logo image in **token_symbol.svg** format (ex: **gnot.svg**) in the [/images/token](https://github.com/onbloc/adena-resource/tree/main/images/token) folder.
		- An entry in the `tokens.json` file that matches the following format.

```jsonc
//token symbol in capital letters (ex: GNOT)
[TOKEN_SYMBOL: string]: {
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
	- Apps
		- A 34x34 app logo image in **project_name.svg** format (ex: **gnoscan.svg**) in the [/images/apps](https://github.com/onbloc/adena-resource/tree/main/images/dapp) folder.
		- An entry in the `apps.json` file that matches the following format.

```jsonc
{
	//project symbol in capital letters without spaces or underscores (ex: GNOSCAN)
	"type": string,
	//project name (ex: Gnoscan)
	"name": string,
	//a description of the project (38 characters max)
	"description": string,
	//link that points to the svg file of your logo
	"logo": string,
	//the domain address of your web application (ex: https://gnoscan.io)
	"link": string,
	//whether the app is displayed on the menu or not
	"display": boolean,
	//order on the list of apps - be sure to put the succeeding number of the last app entry
	"order": number
	//**REMOVE ALL COMMENTS BEFORE THE ACTUAL PR**
}
```
5.  Push changes to your fork.
6.  Open a PR in our repository and wait for us to review and pull your changes.

Our members will review your submission and accept your PR ONLY if it follows the correct format.

Although we're managing this list for Adena's prodcuts, we welcome anyone in the community to use resources provided on this repository to display logos & symbols of projects or RPC/API Endpoints for chains on your dapps, lists, data aggregators, or any where applicable.

## Disclaimer
The Adena Team ("we") allows anyone to submit information about any projects.

Although we throughly review the submissions, we do not gurantee the integrity of projects on this list.

The approval of a submission is not an endorsement nor investment advice of any assets.

In no event shall the Adena Team be liable for your damages resulting from investments in assets included in this repository.

The Adena Team reserves the right to reject or remove project submissions at any time at our sole discretion.
