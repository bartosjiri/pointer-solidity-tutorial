# Pointer: Solid Solidity

A repository for the [Pointer](https://www.pointer.gg/)'s *"[Solid Solidity](https://www.pointer.gg/tutorials/solid-solidity)"* project.

## Debriefing

During the project, the following tasks have been accomplished:
- Deploy a custom contract ([Etherscan link](https://rinkeby.etherscan.io/address/0x386202d7744234A28A689A4A1E60fD9C472EC4fC))
- Build and deploy a dedicated website ([Website link](https://pointer-solidity-keyboards.netlify.app/))

<hr />

## Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/)

## Development

#### Blockchain scripts

1. Install project dependencies:
	```
    yarn
    ```
2. Copy the `.env.example` file as `.env` and provide values for the first two fields.
3. Execute the deployment script:
	```
    npx hardhat run scripts/deploy.js --network rinkeby
    ```
4. Add the contract address to the `.env` file.

#### Frontend client

1. Start the application in development mode:
	```
    yarn dev
    ```

## Deployment

1. Generate the production build of the application:
	```
    yarn build
    ```
2. Using the web server of your preference, publish the contents of the generated `build` directory.

## Resources
- [Pointer: Solid Solidity](https://www.pointer.gg/tutorials/solid-solidity)