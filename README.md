<div align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://github.com/wattnet/.github/raw/main/images/wattnet-logo-full-dark-transparent-cropped.png" />
    <source media="(prefers-color-scheme: light)"
            srcset="https://github.com/wattnet/.github/raw/main/images/wattnet-logo-full-light-transparent-cropped.png" />
    <img src="https://github.com/wattnet/.github/raw/main/images/wattnet-logo-full-light-transparent-cropped.png"
         alt="Wattnet Logo"
         width="300" />
  </picture>
</div>

# Keycloak Theme

<p align="center">
    <i>🚀 <a href="https://keycloakify.dev">Keycloakify</a> v11 starter 🚀</i>
    <br/>
    <br/>
</p>

# Quick start

```bash
git clone https://github.com/keycloakify/keycloakify-starter
cd keycloakify-starter
yarn install # Or use an other package manager, just be sure to delete the yarn.lock if you use another package manager.
```

# Testing the theme locally

[Documentation](https://docs.keycloakify.dev/testing-your-theme)

# How to customize the theme

[Documentation](https://docs.keycloakify.dev/customization-strategies)

# Building the theme

You need to have [Maven](https://maven.apache.org/) installed to build the theme (Maven >= 3.1.1, Java >= 7).  
The `mvn` command must be in the $PATH.

-   On macOS: `brew install maven`
-   On Debian/Ubuntu: `sudo apt-get install maven`
-   On Windows: `choco install openjdk` and `choco install maven` (Or download from [here](https://maven.apache.org/download.cgi))

```bash
npm run build-keycloak-theme
```

Note that by default Keycloakify generates multiple .jar files for different versions of Keycloak.  
You can customize this behavior, see documentation [here](https://docs.keycloakify.dev/features/compiler-options/keycloakversiontargets).

# Initializing the account theme

```bash
npx keycloakify initialize-account-theme
```

# Initializing the email theme

```bash
npx keycloakify initialize-email-theme
```

# GitHub Actions

The starter comes with a generic GitHub Actions workflow that builds the theme and publishes
the jars [as GitHub releases artifacts](https://github.com/keycloakify/keycloakify-starter/releases/tag/v10.0.0).  
To release a new version **just update the `package.json` version and push**.

To enable the workflow go to your fork of this repository on GitHub then navigate to:
`Settings` > `Actions` > `Workflow permissions`, select `Read and write permissions`.

## Funding and acknowledgments

This work is funded by the European Union’s Horizon Europe research and innovation programme through the **[GreenDIGIT](https://greendigit-project.eu/)** project, under grant agreement **[101131207](https://cordis.europa.eu/project/id/101131207)**.

<div align="left">
  <img src="https://github.com/wattnet/.github/raw/main/images/EN_FundedbytheEU_RGB_POS.png" alt="EU Funded Logo" width="260"/>
  <img src="https://github.com/wattnet/.github/raw/main/images/GreenDIGIT%20logo%20color%20horizontal2.png" alt="GreenDIGIT Logo" width="230"/>
</div>

##### © 2026 Spanish National Research Council (CSIC). All rights reserved.
