# Extension schemas 

When creating the [YAML files](https://www.dynatrace.com/support/help/shortlink/extension-yaml) for the Dynatrace Extensions 2.0 framework, the extension schemas are an efficient tool for your extension validation, code completion, and in-code documentation. 

This repository hosts the official Extensions 2.0 schemas for each Dynatrace version. 

Schema releases are coupled with the [Dynatrace release lifecycle](https://www.dynatrace.com/support/help/shortlink/release-notes-saas) and are named and tagged with the schema version, for example, `1.260.0`. 

A schema release consists of:
* The schema JSON files in *assets*. 
* The release changelog in *description*.

## Access schemas
* Specific version
  * https://github.com/dynatrace-extensions/extensions-schemas/releases/download/{VERSION}/{SCHEMA_NAME}
* Latest
  * https://github.com/dynatrace-extensions/extensions-schemas/releases/latest/download/{SCHEMA_NAME}

## Documentation
* [Extensions 2.0 doc](https://www.dynatrace.com/support/help/shortlink/extensions20)
  * [YAML file overview](https://www.dynatrace.com/support/help/shortlink/extension-yaml)
  * [WMI datasource tutorial](https://www.dynatrace.com/support/help/shortlink/wmi-tutorial-00)

## Extensions Copilot 
For extension development with snippets and real-time validation we recommend using [Dynatrace extensions add-on for VSCode](https://developer.dynatrace.com/develop/dynatrace-extensions-vscode/).
