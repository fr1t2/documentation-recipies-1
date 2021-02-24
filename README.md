# Documentation

> Refresh of the content for the Quantum Resistant Ledger.

The goal of the refresh is to simplify and categorize the documentation, breaking complex concepts into smaller pieces. These pieces can be presented in levels of depth. We will categorize the documentation into 3 classifications:

| Class  | Description | Link |
|----------|----------|------|
| Consumer | Written to basic user functionality | [consumer recipes](/consumer) |
| Advanced | In-depth and advanced uses | [advanced recipes](/advanced) |
| Developer| Complex and advanced integration docs | [developer](/developer) |



## Recipe Structure

A recipe consists of a basic explanation of the function of the recipe and the actual steps required to replicate the task. 

The documents are written in Markdown syntax to make integration into multiple systems simple while keeping the learning curve fairly low/

> For information on getting started with markdown [please see this great guide](https://www.markdownguide.org/getting-started/)


## File Structure


Each category has a host of documents ranging from creating a new wallet to sending automaticAPI requests broken into sub-directories. The goal is to keep these concise and easy to reference for later projects or incorporation into documentation. 

**Example layout** [*consumer*](/consumer) --> [*ecosystem*](/consumer/ecosystem) --> [*wallets*](/consumer/ecosystem/wallets) --> [*web*](/consumer/ecosystem/wallets/web) --> [*create-a-new-wallet.md*](/consumer/ecosystem/wallets/web/create-a-new-wallet.md)

Each end subdirectory should contain any photos or other related rich content for that document in a root assets directory, with all assets in a similar named internal directory

> For the example above, any photos or video files I have should go in the following location [/consumer/ecosystem/wallets/web/assets/create-a-new-wallet/{DOCUMENT_ASSETS}](/consumer/ecosystem/wallets/web/assets/create-a-new-wallet/example.txt)

## Contributing

To contribute to the repo, fork this repo into your own account, make any changes and submit a PR to the master repo here. 

For help getting started or if you run into any issues, [please reach out for support in our discord chat](https://discord.gg/punXRMM).

