this is copy paste of karabiner event viewer device IDs

# from old karabiner
;;* Devices, Applications and Input Sources  ==================================
	:devices {
			:macbook-internal [{:product_id 631 :vendor_id 1452}]
			
            :uhk [{:product_id 24866 :vendor_id 7504}]
			:uhk-2 [{:product_id 24868 :vendor_id 7504}]
		
            :logitech-mouse [{:product_id 49738 :vendor_id 1133}]
			;; TODO add other gaming mouse, 
			}
	
    apple :vendor_id 1452
    UHK :vendor_id 7504
    
    :Mbps {
        [
            ["REGEX"]
            ["REGEX"]
            :macbook-internal0 [{:product_id 631 :vendor_id 1452}]
            :macbook-internal1 [{:product_id 4294970359 :vendor_id 1452}]
            

        ]
        }
    :applications {
		;; template  
		;; drafts com.agiletortoise.Drafts-OSX
		:dynalist ["^io\\.dynalist$"]
		:Chromes      ["^com\\.google\\.Chrome$", "^org\\.chromium\\.Chromium$", "^com\\.google\\.Chrome\\.canary$"]
		
        :Terminals     ["^com\\.apple\\.Terminal$", "^com\\.googlecode\\.iterm2$", "^co\\.zeit\\.hyperterm$", "^co\\.zeit\\.hyper$", "^io\\.alacritty$", "^net\\.kovidgoyal\\.kitty$"]
		
        :Finder           ["^com\\.apple\\.finder$"]
		:Debuggers   ["^org\\.mozilla\\.firefox$", "^org\\.mozilla\\.firefoxdeveloperedition$", "^com\\.google\\.Chrome$", "^org\\.chromium\\.Chromium$", "^com\\.google\\.Chrome\\.canary$", "^com\\.apple\\.Safari$", "^com\\.microsoft\\.VSCode$"]
		:Browsers      ["^org\\.mozilla\\.firefox$", "^org\\.mozilla\\.firefoxdeveloperedition$", "^com\\.google\\.Chrome$", "^org\\.chromium\\.Chromium$", "^com\\.google\\.Chrome\\.canary$", "^com\\.apple\\.Safari$"]
		}



		:input-sources {
	 		:squirrel {:input_mode_id   "com.googlecode.rimeime.inputmethod.Squirrel"
						:input_source_id "com.googlecode.rimeime.inputmethod.Squirrel.Rime"
						:language        "zh-Hans"}
			:us {:input_mode_id   ""
					:input_source_id "com.apple.keylayout.US"
					:language        "en"}
			}

# from mx3 2024-10-16
[
    {
        "device_id": 4294970359,
        "device_identifiers": { "is_keyboard": true },
        "is_apple": true,
        "is_built_in_keyboard": true,
        "location_id": 49,
        "manufacturer": "Apple",
        "product": "Apple Internal Keyboard / Trackpad",
        "transport": "FIFO"
    },
    {
        "device_id": 4294970405,
        "device_identifiers": { "is_pointing_device": true },
        "is_apple": true,
        "is_built_in_pointing_device": true,
        "location_id": 49,
        "manufacturer": "Apple",
        "product": "Apple Internal Keyboard / Trackpad",
        "transport": "FIFO"
    },
    {
        "device_id": 4295704614,
        "device_identifiers": {
            "is_keyboard": true,
            "product_id": 49738,
            "vendor_id": 1133
        },
        "location_id": 34799616,
        "manufacturer": "Logitech",
        "product": "Gaming Mouse G600",
        "serial_number": "E1A16779F19B0017",
        "transport": "USB"
    },
    {
        "device_id": 4295704612,
        "device_identifiers": {
            "is_pointing_device": true,
            "product_id": 49738,
            "vendor_id": 1133
        },
        "location_id": 34799616,
        "manufacturer": "Logitech",
        "product": "Gaming Mouse G600",
        "serial_number": "E1A16779F19B0017",
        "transport": "USB"
    },
    {
        "device_id": 4295712618,
        "device_identifiers": {
            "is_keyboard": true,
            "is_virtual_device": true,
            "product_id": 591,
            "vendor_id": 1452
        },
        "manufacturer": "pqrs.org",
        "product": "Karabiner DriverKit VirtualHIDKeyboard 1.8.0",
        "serial_number": "pqrs.org:Karabiner-DriverKit-VirtualHIDKeyboard"
    },
    {
        "device_id": 4295727936,
        "device_identifiers": {
            "is_pointing_device": true,
            "is_virtual_device": true,
            "product_id": 10202,
            "vendor_id": 5824
        },
        "manufacturer": "pqrs.org",
        "product": "Karabiner DriverKit VirtualHIDPointing 1.8.0",
        "serial_number": "pqrs.org:Karabiner-DriverKit-VirtualHIDPointing"
    },
    {
        "device_id": 4294972395,
        "device_identifiers": {
            "is_keyboard": true,
            "product_id": 34304,
            "vendor_id": 1452
        },
        "is_apple": true,
        "is_built_in_touch_bar": true,
        "manufacturer": "Apple Inc.",
        "product": "TouchBarUserDevice"
    }
]