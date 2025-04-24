# proactions-schema

## Configuration

You can use the following configuration to use this schema in VS Code:

_.vscode/settings.json_
```json
{
  "yaml.customTags": ["!include scalar"],
  "yaml.schemas": {
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/ai-kit.schema.json": [
      "*.ai-kit.yaml"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-services.schema.json": [
      "*.ai-kit.serv.yaml"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-floatingMenu.schema.json": [
      "*.ai-kit.menu.yaml"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-templates.schema.json": [
      "*.ai-kit.templ.yaml"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-section.schema.json": [
      "*.ai-kit.sect.yaml"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-step.schema.json": [
      "*.ai-kit.step.yaml"
    ]
  }
}
```
