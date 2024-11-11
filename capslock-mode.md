2024-11-11 having issues with capslock mode so remove and placing here... trying out tab...


```clojure
;;? Tab Mode
{:des "tab-mode" :rules [ :tab-mode ;;*= CAPSLOCK MODE =======================
		
    ]}
```

```clojure
;;? CAPSLOCK MODE (⇪µ)
{:des "capslock mode" :rules [ :capsµ ;;*= CAPSLOCK MODE =======================
        ;; capslock as hyper (⌃⌥⇧⌘)
		[:escape :!TOSCescape];;• capslock+escape for ⌃⌥⇧⌘+escape
		[:f1 :!TOSCf1];;• capslock+f1 for ⌃⌥⇧⌘+f1
		[:f2 :!TOSCf2] ;;• capslock+f2 for ⌃⌥⇧⌘+f2
		[:f3 :!TOSCf3] ;;• capslock+f3 for ⌃⌥⇧⌘+f3
		[:f4 :!TOSCf4] ;;• capslock+f4 for ⌃⌥⇧⌘+f4
		[:f5 :!TOSCf5] ;;• capslock+f5 for ⌃⌥⇧⌘+f5
		[:f6 :!TOSCf6] ;;• capslock+f6 for ⌃⌥⇧⌘+f6
		[:f7 :!TOSCf7] ;;• capslock+f7 for ⌃⌥⇧⌘+f7
		[:f8 :!TOSCf8] ;;• capslock+f8 for ⌃⌥⇧⌘+f8
		[:f9 :!TOSCf9] ;;• capslock+f9 for ⌃⌥⇧⌘+f9
		[:f10 :!TOSCf10]  ;;• capslock+f10 for ⌃⌥⇧⌘+f10
		[:f11 :!TOSCf11] ;;• capslock+f11 for ⌃⌥⇧⌘+f11
		[:f12 :!TOSCf12] ;;• capslock+f12 for ⌃⌥⇧⌘+f12
		[:grave_accent_and_tilde :!TOSCgrave_accent_and_tilde] ;;• capslock+~ for ⌃⌥⇧⌘+~        
		[:1 :!TOSC1] ;;• capslock+1 for ⌃⌥⇧⌘+1
		[:!C1 [:rayfetti]] ;;• capslock+1 for ⌃⌥⇧⌘+1
        [:2 :!TOSC2] ;;• capslock+2 for ⌃⌥⇧⌘+2
		[:3 :!TOSC3] ;;• capslock+3 for ⌃⌥⇧⌘+3
		[:4 :!TOSC4] ;;• capslock+4 for ⌃⌥⇧⌘+4
		[:5 :!TOSC5] ;;• capslock+5 for ⌃⌥⇧⌘+5
		[:6 :!TOSC6] ;;• capslock+6 for ⌃⌥⇧⌘+6
		[:7 :!TOSC7] ;;• capslock+7 for ⌃⌥⇧⌘+7
		[:8 :!TOSC8] ;;• capslock+8 for ⌃⌥⇧⌘+8
		[:9 :!TOSC9] ;;• capslock+9 for ⌃⌥⇧⌘+9
		[:0 :!TOSC0] ;;• capslock+0 for ⌃⌥⇧⌘+0
		[:hyphen :!TOSChyphen] ;;• capslock+- for ⌃⌥⇧⌘+-
		[:equal_sign :!TOSCequal_sign] ;;• capslock+= for ⌃⌥⇧⌘+=
		[:delete_or_backspace :!TOSCdelete_or_backspace] ;;• ✧+⌫ for ⌃⌥⇧⌘+⌫
		[:tab :!TOSCtab] ;;• capslock+tab for ⌃⌥⇧⌘+tab		
		[:q :!TOSCq] ;;• capslock+q for ⌃⌥⇧⌘+q
		[:w :!TOSCw] ;;• capslock+w for ⌃⌥⇧⌘+w
		[:e :!TOSCe] ;;• capslock+e for ⌃⌥⇧⌘+e
		[:r :!TOSCr] ;;• capslock+r for ⌃⌥⇧⌘+r
		[:t :!TOSCt] ;;• capslock+t for ⌃⌥⇧⌘+t
		[:y :!TOSCy] ;;• capslock+y for ⌃⌥⇧⌘+y
		[:u :!TOSCu] ;;• capslock+u for ⌃⌥⇧⌘+u
		[:i :!TOSCi] ;;• capslock+i for ⌃⌥⇧⌘+i
		[:o :!TOSCo] ;;• capslock+o for ⌃⌥⇧⌘+o
		[:p :!TOSCp] ;;• capslock+p for ⌃⌥⇧⌘+p
		[:open_bracket :!TOSCopen_bracket] ;;• capslock+[ for ⌃⌥⇧⌘+[
		[:close_bracket :!TOSCclose_bracket] ;;• capslock+] for ⌃⌥⇧⌘+]
		[:backslash :!TOSCbackslash] ;;• capslock+\ for ⌃⌥⇧⌘+\

		[:a :!TOSCa] ;;• capslock+a for ⌃⌥⇧⌘+a
		[:s :!TOSCs] ;;• capslock+s for ⌃⌥⇧⌘+s
		[:d :!TOSCd] ;;• capslock+d for ⌃⌥⇧⌘+d
		[:f :!TOSCf] ;;• capslock+f for ⌃⌥⇧⌘+f
		[:g :!TOSCg] ;;• capslock+g for ⌃⌥⇧⌘+g
		[:h :!TOSCh] ;;• capslock+h for ⌃⌥⇧⌘+h
		[:j :!TOSCj] ;;• capslock+j for ⌃⌥⇧⌘+j
		[:k :!TOSCk] ;;• capslock+k for ⌃⌥⇧⌘+k
		[:l :!TOSCl] ;;• capslock+l for ⌃⌥⇧⌘+l
		[:semicolon :!TOSCsemicolon] ;;• capslock+; for ⌃⌥⇧⌘+;
		[:quote :!TOSCquote] ;;• capslock+' for ⌃⌥⇧⌘+'
		[:return_or_enter :!TOSCreturn_or_enter] ;;• capslock+return for ⌃⌥⇧⌘+return
		[:z :!TOSCz] ;;• capslock+z for ⌃⌥⇧⌘+z
		[:x :!TOSCx] ;;• capslock+x for ⌃⌥⇧⌘+x
		[:c :!TOSCc] ;;• capslock+c for ⌃⌥⇧⌘+c
		[:v :!TOSCv] ;;• capslock+v for ⌃⌥⇧⌘+v
		[:b :!TOSCb] ;;• capslock+b for ⌃⌥⇧⌘+b
		[:n :!TOSCn] ;;• capslock+n for ⌃⌥⇧⌘+n
		[:m :!TOSCm] ;;• capslock+m for ⌃⌥⇧⌘+m
		[:comma :!TOSCcomma] ;;• capslock+, for ⌃⌥⇧⌘+,
		[:period :!TOSCperiod] ;;• capslock+. for ⌃⌥⇧⌘+.
		[:slash :!TOSCslash] ;;• capslock+/ for ⌃⌥⇧⌘+/
		
]}
```