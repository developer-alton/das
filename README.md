# das manual

SetAnim
	@SetAnim&{nm="",loop=3.0,face="",sos=""}

NextAnim
	@NextAnim&{nm=""}

StopAnim
	@StopAnim

PlayEvt 
	@playEvt&{md="",tp="",nm="",ext=""}	

		md = "scene", "action", "system", "notify"

PlaySnd
	@playSnd&{md="", tp="",nm="",vol=0.1,cool=1.0,loop=1}

PlayBgSnd
	@PlayBgSnd&{tp="",nm="",vol=0.1,cool=1.0}

PlayFormBgSnd
	@PlayFormBgSnd&{esp=test.esp,fid=0x00000,vol=0.5}

SetPos
	@setPos&{md="", rotate="",offset="",side=""}

SetStatus	
    @SetStatus&{md="", expression="",eyes="",mouth="",tongue="",sos=""}

    	expression
    		- happy, smile, lwink(rwink), disguised, surprised, scary, angry, pain (painMild, painStrong), shamed, concentrate, embarrased

    		- kiss, aroused, moan, moanMild, moanStrong, orgasm

    		- oh, ah, ee
    	eyes
    		- closed, up, down, left, right, center
    	mouth
    		- closed, tiny, small, middle, big
    	tongue    	
    		- kiss, lick, itch, down

ShowMsg
	@ShowMsg&{msg=""}

PlayCstSnd
	@PlayCstSnd&{esp=test.esp,fid=0x00000,vol=0.5}"

PlayCstBgSnd
	@PlayCstBgSnd&{esp=test.esp,fid=0x00000,vol=0.5}"

PlayBumpEvt
	@PlayBumpEvt&forward


	 
