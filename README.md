Parameter(s):
	_title 		: STRING - Default Value  : ""
	_text 		: STRING - Default Value  : ""
	_stripColor	: ARRAY  - Default Value  : [0.043,0.486,0.769,1]
	_sound 		: STRING - Default Value  : "additemfailed"

	If you don't want to use sound, add "" in the fourth params. ["Error","Oops it's not possible my friend",nil,"mySound"]
	If you want a sound but you don't want to change the strip color, use nil as third params : ["Error","Oops it's not possible my friend",nil,""]

	Exemple : ["Error","Oops it's not possible my friend",nil,""] call UPM_fnc_showNotification;
