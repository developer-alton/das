# DAS manual
animation annotations that can make a specific scene by using hkanno64 Animation Annotation Tools (https://www.nexusmods.com/skyrimspecialedition/mods/54244)

## Annotations
SetAnim
	@SetAnim&{nm="",loop=3.0,face="",sos=""}

PlayAnim
	@PlayAnim&{nm=""}

PlayEvt 
	@playEvt&{md="",tp="",nm="",ext=""}	

		md = "scene", "action", "system", "notify"

PlaySnd
	@playSnd&{md="", tp="",nm="",vol=0.1,expression="",eyes="",mouth="",tongue="",sos="",topic=""}
    	expression
    		- happy, smile, lwink(rwink), disguised, surprised, scary, angry, pain (painMild, painStrong), shamed, concentrate, embarrased

    		- kiss, aroused, moan, moanMild, moanStrong, orgasm

    		- oh, ah, ee
    	eyes
    		- closed, up, down, left, right, center, reset
    	mouth
    		- closed, tiny, small, middle, big, reset
    	tongue    	
    		- leftRight, rightLeft, downUp, center, left, right, up, upLong, down, downLong, reset
		
	topic
		- 
		
PlayFormSnd
	@PlayFormSnd&{esp=test.esp,fid=0x00000,vol=0.5}"
	
PlayBgSnd
	@PlayBgSnd&{tp="",nm="",vol=0.1,cool=1.0}

PlayFormBgSnd
	@PlayFormBgSnd&{esp=test.esp,fid=0x00000,vol=0.5}

SetPos
	@setPos&{md="", rotate="",offset="",side=""}

ShowMsg
	@ShowMsg&{msg=""}
	
## Papyus script



## Examples

	 
