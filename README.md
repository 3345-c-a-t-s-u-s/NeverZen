# NeverZen
NEVERLOSE + GameSense
```lua
local neverwin = require(script:WaitForChild('ModuleScript'));
local notifi = neverwin:CreateNotifier();

local window = neverwin.new({
	Name = "NEVERLOSE.CC",
	Resizable = true,
	Shadow = true,
	Keybind = Enum.KeyCode.LeftControl
})

window:AddLabel("General")

local FishingTab = window:AddTab({
	Name = "Fishing",
	Icon = 'map'
});

local sec1 = FishingTab:AddSection({
	Name = 'Fishing',
	Position = 'left'	
});

local sec2 = FishingTab:AddSection({
	Name = 'Rods',
	Position = 'right'	
});

local Example = FishingTab:AddSection({
	Name = 'Example',
	Position = 'right'	
});

sec1:AddToggle({
	Name = 'Auto Cast'
})

sec1:AddToggle({
	Name = 'Auto Shake'
})

sec1:AddToggle({
	Name = 'Auto Reel'
})

sec1:AddLabel('Settings')

sec1:AddToggle({
	Name = 'Legit Mode'
})

sec1:AddDropdown({
	Name = 'Shake Method',
	Values = {'Fast','Slow'},
	Default = 'Fast'
})

sec2:AddToggle({
	Name = 'Auto Rod'
})

sec2:AddDropdown({
	Name = 'Rod',
	Values = {"AK-47",'MAC-10'},
	Default = 'AK-47',
	Callback = function(a)
		print('ij')
		notifi.new('Rod Selected','asdwasdwad: '..a..'\n12839812093091391389139203213123\n9830138398903381931\[[[dwa[da[ddadadad'..debug.traceback())
	end,
})


Example:AddToggle({
	Name = 'Toggle'
})

Example:AddSlider({
	Name = 'Slider'
})

Example:AddKeybind({
	Name = 'Keybind',
	Callback = print
})

Example:AddButton({
	Name = 'Button'
})

Example:AddLabel('Label')

Example:AddDropdown({
	Name = 'Dropdown (Single)',
	Values = {'index 1','index 2','index 3'},
	Default = 'index 1'
})

Example:AddDropdown({
	Name = 'Dropdown (Multi)',
	Values = {'index 1','index 2','index 3'},
	Default = {'index 1'},
	Multi = true
})


do
	window:AddLabel("General")

	local FishingTab = window:AddTab({
		Name = "Fishing",
		Icon = 'map'
	});

	local sec1 = FishingTab:AddSection({
		Name = 'Fishing',
		Position = 'left'	
	});

	local sec2 = FishingTab:AddSection({
		Name = 'Rods',
		Position = 'right'	
	});

	local Example = FishingTab:AddSection({
		Name = 'Example',
		Position = 'right'	
	});

	sec1:AddToggle({
		Name = 'Auto Cast'
	})

	sec1:AddToggle({
		Name = 'Auto Shake'
	})

	sec1:AddToggle({
		Name = 'Auto Reel'
	})

	sec1:AddLabel('Settings')

	sec1:AddToggle({
		Name = 'Legit Mode'
	})

	sec1:AddDropdown({
		Name = 'Shake Method',
		Values = {'Fast','Slow'},
		Default = 'Fast'
	})

	sec2:AddToggle({
		Name = 'Auto Rod'
	})

	sec2:AddDropdown({
		Name = 'Rod',
		Values = {"AK-47",'MAC-10'},
		Default = 'AK-47',
		Callback = function(a)
			print('ij')
			notifi.new('Rod Selected','asdwasdwad: '..a..'\n12839812093091391389139203213123\n9830138398903381931\[[[dwa[da[ddadadad'..debug.traceback())
		end,
	})

	Example:AddToggle({
		Name = 'Toggle'
	})

	Example:AddSlider({
		Name = 'Slider'
	})

	Example:AddKeybind({
		Name = 'Keybind',
		Callback = print
	})

	Example:AddButton({
		Name = 'Button'
	})

	Example:AddLabel('Label')

	Example:AddDropdown({
		Name = 'Dropdown (Single)',
		Values = {'index 1','index 2','index 3'},
		Default = 'index 1'
	})

	Example:AddDropdown({
		Name = 'Dropdown (Multi)',
		Values = {'index 1','index 2','index 3'},
		Default = {'index 1'},
		Multi = true
	})
end
```
