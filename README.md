# plugin-signer

This project acts as a way for us to sign grafana plugins from repositories as our required root urls.

This is due to Grafana making it difficult to release custom plugins on their marketplace.

## Usage
Use the action https://github.com/intergral/plugin-signer/actions/workflows/signer.yaml to sign a plugin.

Enter the inputs
 - rootUrls: the comma seperated root urls to sign with
 - repository: the name of the github repo to sign
 - ref: the ref of the repo to sign (this should be the tag version e.g. v0.03)
 