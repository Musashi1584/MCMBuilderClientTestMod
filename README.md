# MCMBuilderClientTestMod

```
[MCMBuilderClientTestMod.TestMod_MCM_Builder]
+MCMPages = { \\
	"TESTMOD_SETTINGS_PAGE":{ \\
		"SaveConfigManager": "TestModUserSettingsConfigManager",\\
		"EnableResetButton": "true", \\
		"TESTMOD_SETTINGS_GROUP_1":{ \\
			"A_BOOL_PROPERTY":  { "Type": "Checkbox" }, \\
			"A_FLOAT_PROPERTY": { "Type": "Slider", "SliderMin": "0.0", "SliderMax": "1.0", "SliderStep":"0.1" }, \\
			"A_INT_PROPERTY":   { "Type": "Spinner", "Options": "1, 2, 3, 4, 5, 6, 7, 8, 9, 10" }, \\
			"A_STRING_PROPERTY":{ "Type": "Dropdown", "Options": "Bar, Foo, Test" }, \\
		}, \\
		"TESTMOD_SETTINGS_GROUP_2":{ \\
			"A_LABEL":          { "Type": "Label" }, \\
		}, \\
	}, \\
}
```
![Screenshit](https://github.com/Musashi1584/MCMBuilderClientTestMod/blob/master/Screenshot.jpg)
