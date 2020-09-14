
---
title: Currencies
---

# Resources for Currencies


### Currency

|         Name         |      Format       | Required | Read Only | Max size | Not filterable | Description |
| :------------------- | :---------------- | :------- | :-------- | :------- | :------------- | :---------- |
| **names**            |                   |          |           |          |                |             |
| **name**             | isGenericName     | true     |           | 255      | true           |             |
| **symbol**           |                   |          |           | 255      |                |             |
| **iso_code**         | isLanguageIsoCode | true     |           | 3        |                |             |
| **numeric_iso_code** | isNumericIsoCode  |          |           | 3        |                |             |
| **precision**        | isInt             |          |           |          |                |             |
| **conversion_rate**  | isUnsignedFloat   | true     |           |          |                |             |
| **deleted**          | isBool            |          |           |          |                |             |
| **active**           | isBool            |          |           |          |                |             |
| **unofficial**       | isBool            |          |           |          |                |             |
| **modified**         | isBool            |          |           |          |                |             |
| **pattern**          |                   |          |           | 255      |                |             |


### Example

```xml
<?xml version="1.0" encoding="UTF-8"?>
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
<currency>
	<id><![CDATA[]]></id>
	<names><language id="1"></language><language id="2"></language></names>
	<name><![CDATA[]]></name>
	<symbol><language id="1"></language><language id="2"></language></symbol>
	<iso_code><![CDATA[]]></iso_code>
	<numeric_iso_code><![CDATA[]]></numeric_iso_code>
	<precision><![CDATA[]]></precision>
	<conversion_rate><![CDATA[]]></conversion_rate>
	<deleted><![CDATA[]]></deleted>
	<active><![CDATA[]]></active>
	<unofficial><![CDATA[]]></unofficial>
	<modified><![CDATA[]]></modified>
	<pattern><language id="1"></language><language id="2"></language></pattern>
</currency>
</prestashop>

```

