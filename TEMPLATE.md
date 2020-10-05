Account age: **{{ ACCOUNT_AGE }}** years

Top 8 most used languages across your repositories:

{{ LANGUAGE_TEMPLATE_START }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}

Top 4 most used languages across your repositories:

{{ LANGUAGE_TEMPLATE_START:max=4 }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}
