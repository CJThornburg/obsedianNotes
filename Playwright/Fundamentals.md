dir setup
![[Pasted image 20240802114321.png]]
`import {test, expect} from '@playwright/test`

playwright is async

basic test set up
![[Pasted image 20240802114511.png]]



test.skip(...) will skip test

test.only(...) run only that one

wrap tests in describe to make test suites
![[Pasted image 20240805140626.png]]

can tag tests to be able to run a tag of tests
	- @
	- and located at the end of decscription

![[Pasted image 20240805140948.png]]
can also skip a specic tag with 
`npx playwright test --grep-invert @myTag`



# config files
[video](https://www.udemy.com/course/automated-software-testing-with-playwright/learn/lecture/29641330#overview)
playwright.config.ts

ex
-  ![[Pasted image 20240805142034.png]] 
- ![[Pasted image 20240805142235.png]]
- ex command
- ![[Pasted image 20240805142137.png]]



# reporters

sets ouptut pretty much

`--reporter=list` is default

`=line` ouptuts one line,

`=junit` output is in jason format


`=html`  creats a folder and ouptus stuff
	- playrwit-report
![[Pasted image 20240805144138.png]]

- browser/html friendly to look at report