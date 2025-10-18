# proactions-schema

## Configuration

You can use the following configuration to use this schema in VS Code:

_.vscode/settings.json_
```json
{
  "yaml.customTags": ["!include scalar"],
  "yaml.schemas": {
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/ai-kit.schema.json": [
      "*.ai-kit.yaml",
      "*.ai-kit.yaml*"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-services.schema.json": [
      "*.ai-kit.serv.yaml",
      "*.ai-kit.serv.yaml*",
      "*.ai-kit.services.yaml",
      "*.ai-kit.services.yaml*"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-floatingMenu.schema.json": [
      "*.ai-kit.menu.yaml",
      "*.ai-kit.menu.yaml*"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-templates.schema.json": [
      "*.ai-kit.templ.yaml",
      "*.ai-kit.templ.yaml*",
      "*.ai-kit.template.yaml",
      "*.ai-kit.template.yaml*"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-section.schema.json": [
      "*.ai-kit.sect.yaml",
      "*.ai-kit.sect.yaml*",
      "*.ai-kit.section.yaml",
      "*.ai-kit.section.yaml*"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-action.schema.json": [
      "*.ai-kit.action.yaml",
      "*.ai-kit.action.yaml*"
    ],
    "https://raw.githubusercontent.com/em-al-wi/proactions-schema/main/schema/partial-step.schema.json": [
      "*.ai-kit.step.yaml",
      "*.ai-kit.step.yaml*"
    ]
  }
}
```
