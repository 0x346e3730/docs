
---
title: Languages
---

# Resources for Languages


### Language

|         Name         |      Format       | Required | Read Only | Max size | Not filterable | Description |
| :------------------- | :---------------- | :------- | :-------- | :------- | :------------- | :---------- |
| **name**             | isGenericName     | true     |           | 32       |                |             |
| **iso_code**         | isLanguageIsoCode | true     |           | 2        |                |             |
| **locale**           | isLocale          |          |           | 5        |                |             |
| **language_code**    | isLanguageCode    |          |           | 5        |                |             |
| **active**           | isBool            |          |           |          |                |             |
| **is_rtl**           | isBool            |          |           |          |                |             |
| **date_format_lite** | isPhpDateFormat   | true     |           | 32       |                |             |
| **date_format_full** | isPhpDateFormat   | true     |           | 32       |                |             |


### Example

```xml
<?xml version="1.0" encoding="UTF-8"?>
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
<language>
	<id><![CDATA[]]></id>
	<name><![CDATA[]]></name>
	<iso_code><![CDATA[]]></iso_code>
	<locale><![CDATA[]]></locale>
	<language_code><![CDATA[]]></language_code>
	<active><![CDATA[]]></active>
	<is_rtl><![CDATA[]]></is_rtl>
	<date_format_lite><![CDATA[]]></date_format_lite>
	<date_format_full><![CDATA[]]></date_format_full>
</language>
</prestashop>

```

