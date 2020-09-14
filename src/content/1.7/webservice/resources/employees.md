
---
title: Employees
---

# Resources for Employees


### Employee

|             Name             |    Format     | Required | Read Only | Max size | Not filterable | Description |
| :--------------------------- | :------------ | :------- | :-------- | :------- | :------------- | :---------- |
| **id_lang**                  | isUnsignedInt | true     |           |          |                |             |
| **last_passwd_gen**          |               |          | true      |          |                |             |
| **stats_date_from**          | isDate        |          | true      |          |                |             |
| **stats_date_to**            | isDate        |          | true      |          |                |             |
| **stats_compare_from**       | isDate        |          | true      |          |                |             |
| **stats_compare_to**         | isDate        |          | true      |          |                |             |
| **passwd**                   | isPasswd      | true     |           | 255      |                |             |
| **lastname**                 | isName        | true     |           | 255      |                |             |
| **firstname**                | isName        | true     |           | 255      |                |             |
| **email**                    | isEmail       | true     |           | 255      |                |             |
| **active**                   | isBool        |          |           |          |                |             |
| **id_profile**               | isInt         | true     |           |          |                |             |
| **bo_color**                 | isColor       |          |           | 32       |                |             |
| **default_tab**              | isInt         |          |           |          |                |             |
| **bo_theme**                 | isGenericName |          |           | 32       |                |             |
| **bo_css**                   | isGenericName |          |           | 64       |                |             |
| **bo_width**                 | isUnsignedInt |          |           |          |                |             |
| **bo_menu**                  | isBool        |          |           |          |                |             |
| **stats_compare_option**     | isUnsignedInt |          |           |          |                |             |
| **preselect_date_range**     |               |          |           | 32       |                |             |
| **id_last_order**            | isUnsignedInt |          |           |          |                |             |
| **id_last_customer_message** | isUnsignedInt |          |           |          |                |             |
| **id_last_customer**         | isUnsignedInt |          |           |          |                |             |
| **reset_password_token**     | isSha1        |          |           | 40       |                |             |
| **reset_password_validity**  | isDateOrNull  |          |           |          |                |             |
| **has_enabled_gravatar**     | isBool        |          |           |          |                |             |


### Example

```xml
<?xml version="1.0" encoding="UTF-8"?>
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
<employee>
	<id><![CDATA[]]></id>
	<id_lang><![CDATA[]]></id_lang>
	<last_passwd_gen><![CDATA[]]></last_passwd_gen>
	<stats_date_from><![CDATA[]]></stats_date_from>
	<stats_date_to><![CDATA[]]></stats_date_to>
	<stats_compare_from><![CDATA[]]></stats_compare_from>
	<stats_compare_to><![CDATA[]]></stats_compare_to>
	<passwd><![CDATA[]]></passwd>
	<lastname><![CDATA[]]></lastname>
	<firstname><![CDATA[]]></firstname>
	<email><![CDATA[]]></email>
	<active><![CDATA[]]></active>
	<id_profile><![CDATA[]]></id_profile>
	<bo_color><![CDATA[]]></bo_color>
	<default_tab><![CDATA[]]></default_tab>
	<bo_theme><![CDATA[]]></bo_theme>
	<bo_css><![CDATA[]]></bo_css>
	<bo_width><![CDATA[]]></bo_width>
	<bo_menu><![CDATA[]]></bo_menu>
	<stats_compare_option><![CDATA[]]></stats_compare_option>
	<preselect_date_range><![CDATA[]]></preselect_date_range>
	<id_last_order><![CDATA[]]></id_last_order>
	<id_last_customer_message><![CDATA[]]></id_last_customer_message>
	<id_last_customer><![CDATA[]]></id_last_customer>
	<reset_password_token><![CDATA[]]></reset_password_token>
	<reset_password_validity><![CDATA[]]></reset_password_validity>
	<has_enabled_gravatar><![CDATA[]]></has_enabled_gravatar>
</employee>
</prestashop>

```

