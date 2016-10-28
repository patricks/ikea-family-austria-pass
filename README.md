# ikea-family-austria-pass
IKEA Family Austria Pass Package for the iOS / macOS Wallet.app

## Requirements to create a pass file
* Apple Developer Account

##
* Follow the steps at: https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/PassKit_PG/YourFirst.html#//apple_ref/doc/uid/TP40012195-CH2-SW1 to create your pass package signing setup.

## Edit pass.json

* Replace <IKEA_FAMILY_IDENTIFIER> with your passTypeIdentifier.
* Replace <IKEA_FAMILY_TEAM_ID> with your teamIdentifier.
* Replace <IKEA_FAMILY_ID> with your Family Card ID.
* [Optional] Replace <IKEA_FAMILY_NAME> with your/a name.

## Create Pass Package
```./signpass -p IkeaFamily.pass```
