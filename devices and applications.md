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
            :macbook-internal1 [{:product_id 4294970359 :vendorsid 1452}]
            

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



# 



Let me know if you need any further assistance!










Here are all the Karabiner rule values in a single code block:
tv	:KeyboardMaestro    ["^com\\.keyboardmaestro\\.KeyboardMaestro$"]

	:Messages          ["^com\\.apple\\.iMessage$"]
	:Moom              ["^com\\.manytricks\\.Moom$"]
	:Notes             ["^com\\.apple\\.Notes$"]
	:Notion            ["^notion\\.id$"]
	:nvUltra           ["^dev\\.nvUltra\\.nvUltra$"]
	:Obsidian          ["^md\\.obsidian\\.obsidian$"]
	:OmniFocus         ["^com\\.omnigroup\\.OmniFocus$"]
	:Raycast           ["^com\\.raycast\\.Raycast$"]

```
	:2Do               ["^com\\.hogbaysoftware\\.2Do$"]
	:AirBuddy          ["^com\\.airbuddy\\.AirBuddy$"]
	:AppTamer          ["^com\\.stclairsoft\\.AppTamer$"]
	:Bartender         ["^com\\.macbartender\\.Bartender$"]
	:BetterTouchTool   ["^com\\.hegenberg\\.BetterTouchTool$"]
	:Bike              ["^com\\.bike\\.Bike$"]
	:CameraBagPro      ["^com\\.fxcamera\\.CameraBagPro$"]
	:Chronicle         ["^com\\.chronicleapp\\.Chronicle$"]
	:CleanMyMac        ["^com\\.macpaw\\.CleanMyMac$"]
	:CleanShotX        ["^com\\.cleanshot\\.CleanShotX$"]
	:ClearVPN          ["^com\\.clearvpn\\.ClearVPN$"]
	:CommanderOne      ["^com\\.electronic\\.us\\.CommanderOne$"]
	:Craft             ["^com\\.luckymarmot\\.Craft$"]
	:Dash              ["^com\\.kapeli\\.dash$"]
	:DefaultFolderX    ["^com\\.stclairsoft\\.DefaultFolderX$"]
	:DevUtils          ["^com\\.devutils\\.DevUtils$"]
	:Downie            ["^com\\.rogueamoeba\\.Downie$"]
	:Dropzone          ["^com\\.apton\\.Dropzone$"]
	:ForecastBar       ["^com\\.frosty\\.Apps\\.ForecastBar$"]
	:Gemini            ["^com\\.macpaw\\.Gemini$"]
	:Hookmark          ["^com\\.cogsci\\.Hookmark$"]
	:Icon              ["^com\\.icon\\.Icon$"]
	:KeepIt            ["^com\\.culturedcode\\.KeepIt$"]
	:Marked            ["^com\\.brettterpstra\\.Marked$"]
	:MarsEdit          ["^com\\.red-sweater\\.MarsEdit$"]
	:MenubarX          ["^com\\.menubarx\\.MenubarX$"]
	:MindNode          ["^com\\.mindnode\\.MindNode$"]
	:MurmurType        ["^com\\.murmurtype\\.MurmurType$"]
	:NotePlan          ["^com\\.noteplan\\.NotePlan$"]
	:Novabench         ["^com\\.novabench\\.Novabench$"]
	:Numi              ["^com\\.numi\\.Num$"]
	:Paletro           ["^com\\.paletro\\.Paletro$"]
	:PDFSearch         ["^com\\.pdfsearch\\.PDFSearch$"]
	:Permute           ["^com\\.helftone\\.Permute$"]
	:Pulltube          ["^com\\.rebeloper\\.Pulltube$"]
	:Receipts          ["^com\\.receipts\\.Receipts$"]
	:SideNotes         ["^com\\.sidenotes\\.Sidenotes$"]
	:Sip               ["^com\\.glyphs\\.Sip$"]
	:Slidepad          ["^com\\.bettertouchtool\\.Slidepad$"]
	:SnippetsLab       ["^com\\.renfei\\.SnippetsLab$"]
	:Soulver           ["^com\\.acqualia\\.Soulver$"]
	:Squash            ["^com\\.hornet\\.Squash$"]
	:TabFinder         ["^com\\.tabfinder\\.TabFinder$"]
	:TaskPaper         ["^com\\.hogbaysoftware\\.TaskPaper$"]
	:TextSniper        ["^com\\.textsniper\\.TextSniper$"]
	:ToothFairy        ["^com\\.stairways\\.ToothFairy$"]
	:TouchRetouch      ["^com\\.advasoft\\.TouchRetouch$"]
	:Vivid             ["^com\\.vivid\\.Vivid$"]
	:WhisperTranscribe  ["^com\\.whispertranscribe\\.WhisperTranscribe$"]
	:Xnapper           ["^com\\.xnapper\\.Xnapper$"]
	:Yoink             ["^com\\.eternalstorms\\.Yoink$"]
	:1Password         ["^com\\.agilebits\\.onepassword$"]
	:Alfred5           ["^com\\.alfredapp\\.Alfred-5$"]
	:Amphetamine       ["^com\\.stclairsoft\\.Amphetamine$"]
	:AppStore          ["^com\\.apple\\.appstore$"]
	:Automator         ["^com\\.apple\\.Automator$"]
	:Bear              ["^net\\.shinyfrog\\.bear$"]
	:Books             ["^com\\.apple\\.Books$"]
	:Calculator        ["^com\\.apple\\.calculator$"]
	:Calendar          ["^com\\.apple\\.iCal$"]
	:Cardhop           ["^com\\.flexibits\\.cardhop$"]
	:ChatGPT           ["^com\\.openai\\.ChatGPT$"]
	:Chess             ["^com\\.apple\\.chess$"]
	:Clock             ["^com\\.apple\\.clock$"]
	:Contacts          ["^com\\.apple\\.AddressBook$"]
	:Contexts          ["^com\\.zapier\\.Contexts$"]
	:Cursor            ["^com\\.cursor\\.Cursor$"]
	:Developer         ["^com\\.apple\\.DeveloperTools$"]
	:Dictionary        ["^com\\.apple\\.Dictionary$"]
	:Drafts            ["^com\\.agiletortoise\\.Drafts-OSX$"]
	:Dropbox           ["^com\\.getdropbox\\.dropbox$"]
	:FaceTime          ["^com\\.apple\\.facetime$"]
	:Fantastical       ["^com\\.flexibits\\.fantastical$"]
	:FinalCutProTrial  ["^com\\.apple\\.finalcutpro\\.trial$"]
	:FindMy            ["^com\\.apple\\.findmy$"]
	:FontBook          ["^com\\.apple\\.FontBook$"]
	:Freeform          ["^com\\.apple\\.freeform$"]
	:GarageBand        ["^com\\.apple\\.GarageBand$"]
	:GoogleChrome      ["^com\\.google\\.Chrome$"]
	:Home              ["^com\\.apple\\.Home$"]
	:ImageCapture      ["^com\\.apple\\.ImageCapture$"]
	:iMovie            ["^com\\.apple\\.iMovie$"]
	:Insta360Studio    ["^com\\.insta360\\.Insta360Studio$"]
	:iPhoneMirroring    ["^com\\.apple\\.iPhoneMirroring$"]
	:JustPressRecord   ["^com\\.lukepf\\.JustPressRecord$"]
	:KarabinerElements  ["^org\\.pqrs\\.karabiner\\.karabiner_elements$"]
	:KarabinerEventViewer ["^org\\.pqrs\\.karabiner\\.karabiner_eventviewer$"]
	:KeyboardMaestro    ["^com\\.keyboardmaestro\\.KeyboardMaestro$"]
	:KeyCastr           ["^org\\.squrkle\\.KeyCastr$"]
	:Keynote           ["^com\\.apple\\.iWork\\.Keynote$"]
	:Launchpad         ["^com\\.apple\\.launchpad$"]
	:LGHub             ["^com\\.lghub\\.lghub$"]
	:Mail              ["^com\\.apple\\.mail$"]
	:Maps              ["^com\\.apple\\.Maps$"]
	:Messages          ["^com\\.apple\\.iMessage$"]
	:MissionControl    ["^com\\.apple\\.expose$"]
	:Moom              ["^com\\.manytricks\\.Moom$"]
	:Music             ["^com\\.apple\\.Music$"]
	:News              ["^com\\.apple\\.news$"]
	:Notes             ["^com\\.apple\\.Notes$"]
	:NotionWebClipper  ["^notion\\.id\\.clipboard$"]
	:Notion            ["^notion\\.id$"]
	:Numbers           ["^com\\.apple\\.iWork\\.Numbers$"]
	:nvUltra           ["^dev\\.nvUltra\\.nvUltra$"]
	:Obsidian          ["^md\\.obsidian\\.obsidian$"]
	:OmniFocus         ["^com\\.omnigroup\\.OmniFocus$"]
	:Pages             ["^com\\.apple\\.iWork\\.Pages$"]
	:Paper             ["^com\\.fiftythree\\.Paper$"]
	:Passwords         ["^org\\.pqrs\\.karabiner\\.passwords$"]
	:PhotoBooth        ["^com\\.apple\\.PhotoBooth$"]
	:Photos            ["^com\\.apple\\.Photos$"]
	:Plume             ["^org\\.plume\\.Plume$"]
	:Podcasts          ["^com\\.apple\\.podcasts$"]
	:PowerPhotos       ["^com\\.fatcatsoftware\\.PowerPhotos$"]
	:Preview           ["^com\\.apple\\.Preview$"]
	:QuickTimePlayer   ["^com\\.apple\\.QuickTimePlayerX$"]
	:Raycast           ["^com\\.raycast\\.Raycast$"]
	:Reminders         ["^com\\.apple\\.reminders$"]
	:Safari            ["^com\\.apple\\.Safari$"]
	:Setapp            ["^com\\.setapp\\.Setapp$"]
	:Shortcat          ["^org\\.mindnode\\.Shortcat$"]
	:Shortcuts         ["^com\\.apple\\.shortcuts$"]
	:Siri              ["^com\\.apple\\.Siri$"]
	:Slack             ["^com\\.Slack\\.Slack$"]
	:Stickies          ["^com\\.apple\\.Stickies$"]
	:Stocks            ["^com\\.apple\\.stocks$"]
	:SublimeText       ["^com\\.sublimetext\\..*$"]
	:Superkey          ["^org\\.pqrs\\.karabiner\\.superkey$"]
	:Syncthing         ["^syncthing\\.syncthing$"]
	:SystemSettings     ["^com\\.apple\\..*systempreferences.*$"]
	:TextEdit          ["^com\\.apple\\.TextEdit$"]
	:Typinator         ["^com\\..*Typinator.*$"]
	:VisualStudioCode  ["^com\\..*VSCode.*$"]
	:VoiceMemos        ["^.*VoiceMemos.*$"]
	:Tot               ["^.*Tot.*$"]
```

Let me know if you need any further assistance!

2Do
AirBuddy'
App Tamer.app' 
Bartender
BetterTouchTool
Bike'
CameraBag Pro.app' 
Chronicle
CleanMyMac'
CleanShot X.app' 
ClearVPN'
Commander One.app' 
Craft
Dash
Default Folder X.app' 
DevUtils
Downie
Dropzone'
Forecast Bar.app' 
Gemini
Hookmark'
Icon
Keep It Shot.app' 
Marked
MarsEdit
MenubarX
MindNode
MurmurType
NotePlan
Novabench
Numi
Paletro'
PDF Search.app' 
Permute
Pulltube
Receipts
SideNotes
Sip
Slidepad
SnippetsLab
Soulver
Squash'
Tab Finder.app' 
TaskPaper
TextSniper
ToothFairy
TouchRetouch
Vivid
WhisperTranscribe
Xnapper
Yoink
Utilities 
.Karabiner-VirtualHIDDevice-Manager
1Password
Actions'
Alfred 5.app' 
Amphetamine'/System
App Store.app' 
Arc/System
Automator
Bear/System
Books/System
Calculator/System
Calendar
Cardhop
ChatGPT/System
Chess/System
Clock/System
Contacts
Contexts
Cursor
Developer/System
Dictionary
Drafts
Dropbox/System
FaceTime
Fantastical'
Final Cut Pro Trial.app' /System
FindMy'/System
Font Book.app' /System
Freeform
GarageBand'
Google Chrome.app' /System
Home'/System
Image Capture.app' 
iMovie'
Insta360 Studio.app' '/System
iPhone Mirroring.app' '
Just Press Record.app' 
Karabiner-Elements
Karabiner-EventViewer'
Keyboard Maestro.app' 
KeyCastr
Keynote/System
Launchpad
lghub/System
Mail/System
Maps/System
Messages'/System
Mission Control.app' 
Moom/System
Music/System
News/System
Notes'
Notion Web Clipper.app' 
Notion
Numbers
nvUltra
Obsidian
OmniFocus
Pages
Paper/System
Passwords'/System
Photo Booth.app' /System
Photos
Plume/System
Podcasts
PowerPhotos/System
Preview'/System
QuickTime Player.app' 
Raycast/System
Reminders
Safari
Setapp
Shortcat/System
Shortcuts/System
Siri
Slack/System
Stickies/System
Stocks'
Sublime Text.app' 
Superkey
Syncthing'/System
System Settings.app' /System
TextEdit
Typinator
Visual Studio Code.app
VoiceMemos
Tot


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