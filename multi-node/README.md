# Multi-node

A multi-node JElastic environment with ToolsCloud stack ready to go.

## Getting Started

To create the environment, import the `manifest.jps` file using the _raw_ URL ([yeap!](https://raw.githubusercontent.com/toolscloud/deploy-jelastic/master/multi-node/manifest.jps)), instead of the GitHub page ([nope!](https://github.com/toolscloud/deploy-jelastic/blob/master/multi-node/manifest.jps)).

* Click on _IMPORT_:

  ![JElastic Dashboard](/images/dashboard-import.png)

* Paste the URL on the _URL_ tab and click on the button _Import_.

  ![JElastic Dashboard - Import Wizard](/images/dashboard-import-wizard.png)

* That's it! Now, you just need to fill your information to Install the environment

**Important:** You can monitor what's happening behind the scenes, during the installation, on `/console` using the same URL from your provider, like this: `https://[your_cloud_provider]/console`. It's very useful also to test out your own cloud scripts.

# References
* [Environment Import](https://docs.jelastic.com/environment-import) (_from where I get those images_)
