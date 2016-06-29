# tps_signs
Minetest Mod: Signs

If you use [tps_keyword_interact](https://github.com/Cat5TV/tps_keyword_interact), players with the *give* privilege can add a special sign that will *automatically* update the keyword when it changes in keyword.txt:
```
/giveme signs:keyword_sign
```
You will also need to set the text for the Keyword Sign in your conf.
```
tps_signs_text = If you accept these rules, open the chat window and type -k to gain interact.
```
You can change that however you want, but -k must be in there somewhere as that's where the mod places the keyword.
