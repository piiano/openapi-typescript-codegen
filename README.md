<p>
  <a href="https://piiano.com/pii-data-privacy-vault/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://docs.piiano.com/img/logo-developers-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://docs.piiano.com/img/logo-developers.svg">
      <img alt="Piiano Vault" src="https://docs.piiano.com/img/logo-developers.svg" height="40" />
    </picture>
  </a>
</p>

# @piiano/openapi-typescript-codegen

This repository is a fork of the [openapi-typescript-codegen](https://github.com/ferdikoomen/openapi-typescript-codegen) project. It is specifically tailored to generate a TypeScript client for the Piiano Vault API and is not intended for other uses.

For the actual client for Piiano Vault, please visit [@piiano/vault-client](https://www.npmjs.com/package/@piiano/vault-client).

If you wish to generate a client from OpenAPI, check the original [openapi-typescript-codegen](https://www.npmjs.com/package/openapi-typescript-codegen) project or the newer [@hey-api/openapi-ts](https://www.npmjs.com/package/@hey-api/openapi-ts) project that is set to replace it.

## About Piiano Vault

Piiano Vault is the secure home for sensitive personal data. It allows you to safely store sensitive personal data in your own cloud environment with automated compliance controls.

Vault is deployed within your own architecture, next to other DBs used by the applications, and should be used to store the most critical sensitive personal data, such as credit cards and bank account numbers, names, emails, national IDs (e.g. SSN), phone numbers, etc.

The main benefits are:

- Field level encryption, including key rotation.
- Searchability is allowed over the encrypted data.
- Full audit log for all data accesses.
- Granular access controls.
- Easy masking and tokenization of data.
- Out of the box privacy compliance functionality.

More details can be found [on our website](https://piiano.com/pii-data-privacy-vault/) and on the [developers portal](https://docs.piiano.com/).
