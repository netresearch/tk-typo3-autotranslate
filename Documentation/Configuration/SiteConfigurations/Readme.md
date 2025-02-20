# Site Configurations

The basic configuration must be done via the TYPO3 page configuration.

![DeepL](../../Images/SiteConfiguration.png)

### DeepL API-Key

The DeepL API key can be configured in the site configuration module under the DeepL tab.

![DeepL](../../Images/DeepLApiKey.png)

### Translatable Languages

You should set the DeepL source language to your base language, otherwise DeepL will try to detect it based on the text to be translated. (since v1.1.1)
![DeeplSourceLanguage](../../Images/DeeplSourceLanguage.png)

You have to set the DeepL target language for each language to be translated.
![DeeplTargetLanguage](../../Images/DeeplTargetLanguage.png)

### Translatable types

You can choose for which of the supported content types (pages, tt_content or additional tables configured in [extension settings](../ExtensionConfiguration/Readme.md)) the automatic translation should be active.

![checkbox](../../Images/TranslateableElement.png)

### Example configuration for page

In the example, translations for pages are active. The title of the pages and files of the Media type is translated into German and French.

![ExamplePage.png](../../Images/ExamplePage.png)
