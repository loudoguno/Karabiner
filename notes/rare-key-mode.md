# rare-key-mode
rare-key-mode  was attempt to replicate nikitas variable setting and use Karabiner in a different way


```edn
;;• Rare Key Mode ==================================================
;; USAGE: 
	;; jkl ON sdf OFF toggles in-rkm variable to = 1 (set in Simultanous section )
	;; there is a line in :layers for rare-key-mode :key backslash :condi... disabled and not sure how it works
	;;  backlash& is currently disabled but backslash mode is mode (:layer)

{:des "sdf to turn rkm on":rules [
	;; [[:s :d :f] ["in-rkm" 1]]
	[[:s :d :f] ["in-rkm" 0] ["in-rkm" 1] ]
	]}
{:des "sdf to toggle rkm":rules [
	[[:s :d :f] ["in-rkm" 1] ["in-rkm" 0] ]
	[[:j :k :l] ["in-rkm" 0]]
	[:1 :help ["in-rkm" 1] ] ; worked

]}

;; rare-key-mode is a disabled :layer 
	{:des "rare-key-mode"
	  :rules [:rare-key-mode
			[:##1 :help] ; worked
			[:##2 :application] ; is context menu it seems
			[:##3 :print_screen,]
			[:##4 :f14]
			[:##5 :f15]
			[:##6 :f16]
			[:##7 :f17]
			[:##8 :f18]
			[:##8 :f19]
			[:##0 :f20]
			[:##comma :keypad_comma]
			[:##period :keypad_period]
			[:##equal_sign :keypad_equal_sign]
			[:##hyphen :keypad_hyphen]
			[:##slash :keypad_slash]
			[:##p :keypad_plus]
			[:##return_or_enter :keypad_enter]
			[:##i :insert]
			;; ❌ didn't work: find, 

			;; [:!Sspacebar :!Shyphen] ;;- left_shift+spacebar for underscore "_"
			;; [:!Rright_control :hyphen] [:!Sright_control :!Shyphen] ;;- UHK compatability
		]}
```