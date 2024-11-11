# Cheatsheet reference
for things i look up frequently

`n+⇧s` to add text to Notion
`b+f` float bear now
`b+v` add clipboard
`b+c` add hyper-c
`b+m` hook to current window
`b+k` add hook to current window


## :condi (conditionals)

```clojure 
;; example of usage in :simlayer definition
:d& {:key :d :condi :!space-mode}
```


# raycast template
```clojure
;; template alias for racast looks like
:ray "open \"raycast://extensions/%s\""
;; which means your rule can look like
[[:r :a :y][:ray "DEVELOPER-NAME/EXTENSION/ACTION"]] ;;• |ray| for extension:action

;; going further can have queries with e.g. 
[[:r :a :y][:ray "DEVELOPER-NAME/EXTENSION/ACTION?Parameter=Value"]] 
[[:f :n :o :w][:open "raycast://extensions/raycast/raycast-notes/raycast-notes?context=%7B%22id%22:%22628EB8FA-1D86-4881-9154-21CB25F2F1AB%22%7D"]] ;;* now for ACTION

```

## :device
    ;;* references
		;; :ap2 [{:vendor_id 1241, :product_id 41618 }] ;; Anne Pro 2 (mechanical)
		;; :kybs [  ;; group
		;;     {:vendor_id 1452}
		;;     {:vendor_id 76}
				;; ]



## Raycast Notes URL scheme for note ID
if below is the encoded url characters, and they decode to `{"id":"UUID"}`, then the scheme is passing the JSON object array as the "context" parameters value
- the url parameter is "context" and it is = to `{"id":"UUID"}` which is ecoded to: `%7B%22id%22:%22628EB8FA-1D86-4881-9154-21CB25jF2F1AB%22%7D`
and decodes to: `{"id":"628EB8FA-1D86-4881-9154-21CB25F2F1AB"}`