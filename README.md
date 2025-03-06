# translate2025

# Global Web Application Translation Project

## Overview
This repository contains the translation resources for our multi-language web application. We use Weblate as our translation management system to coordinate contributions from our global team of translators.

## Project Structure
- `/locales`: Contains all language files organized by language code
- `/docs`: Documentation for translators
- `/scripts`: Utility scripts for managing the translation workflow

## Supported Languages
Currently, our application is available in:
- English (en) - Source language
- Spanish (es)
- French (fr)
- German (de)
- Japanese (ja)
- Chinese (Simplified) (zh_CN)
- Arabic (ar)
- Russian (ru)

## Translation Workflow

### For Developers
1. Extract translatable strings from the source code
2. Push updated source files to this repository
3. Weblate will automatically detect new strings

### For Translators
1. Access our Weblate instance at `https://translate.example.com`
2. Select your language and component
3. Translate strings, referring to the glossary and style guide
4. Submit translations through the Weblate interface

## Integration
- Our CI/CD pipeline automatically pulls translations from Weblate
- New translations are deployed to production after each release cycle
- Changes to source strings trigger notifications to translators

## Quality Assurance
- All translations undergo automatic quality checks in Weblate
- Context-specific strings have screenshots attached in Weblate
- Peer review is required for critical components

## Getting Access
To contribute to translations:
1. Request access from the localization team
2. Complete the brief onboarding process
3. Review the style guide and glossary

## Contact
- Translation Coordinator: translations@example.com
- Technical Issues: dev-i18n@example.com

## License
Translations are licensed under the same terms as the application itself. See LICENSE file for details.