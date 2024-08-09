
page.goto(<"url">)

page.click(<"selector">)


page.fill(<"selector">, "text to type")   
	- fill in input field


### screenshots
![[Pasted image 20240807094735.png]]
https://www.udemy.com/course/automated-software-testing-with-playwright/learn/lecture/29641348?start=90#overview




### before each (same can be applied for afterEach and afterAll)
![[Pasted image 20240807095019.png]]



### custom funcitons 
- requires page be passed 
![[Pasted image 20240807095400.png]]
calling funcitons after importing normally:
![[Pasted image 20240807095559.png]]



### debugging
#debug

`await page.pause()` in a headed test run will pause execution of test on where it is inserted. and playwright inspector will pop up showing which pause it is :0, inspector will have a play button to continue the run


#debug 
screenshots on fail:
change playwright.config
![[Pasted image 20240807100949.png]]
![[Pasted image 20240807101041.png]]
![[Pasted image 20240807101114.png]]
![[Pasted image 20240807101237.png]]