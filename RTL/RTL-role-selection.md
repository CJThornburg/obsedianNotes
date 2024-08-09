query system https://www.udemy.com/course/react-testing-library-and-jest/learn/lecture/35701622#overview

![[Pasted image 20240607165948.png]]
![[Pasted image 20240607170204.png]][full list](https://www.w3.org/TR/html-aria/#docconformance)


with label
![[Pasted image 20240607175251.png]]


# Tool to help determine query/role to use for selection
![[Pasted image 20240607180228.png]]
[vide - udemy](https://www.udemy.com/course/react-testing-library-and-jest/learn/lecture/35701640#overview)
result:
![[Pasted image 20240607180456.png]]


# Roles more in depth
- [video - component written out - udemy](https://www.udemy.com/course/react-testing-library-and-jest/learn/lecture/35701660#overview)
	- a
	- button
	- footer
	- h1
	- header
	- img
	- multiple input
		- checkbox
		- number
		- radio
		- text
	- li
	- ul
		- ROLE IS list   NOT LISTGROUP
- ![[Pasted image 20240610100651.png]]
- [video - actual selection - udemy](https://www.udemy.com/course/react-testing-library-and-jest/learn/lecture/35701662#overview)
	- ROLES to use to select above, author made it line up with text EXCEPT listgroup is just list
	- ![[Pasted image 20240610101311.png]]


# AccessibleName selection
[video - innertext -udemy](https://www.udemy.com/course/react-testing-library-and-jest/learn/lecture/35701666#overview)
[video - inputs - udemy](https://www.udemy.com/course/react-testing-library-and-jest/learn/lecture/35701670#overview)
- most elements its inner text is the accessibleName
- self closing tag see next section in notes
- `{name: 'textLookingFor'`
	- ex: ![[Pasted image 20240610101829.png]]
	- `/   /i` is a regular expression that removes capitalization sensitivity and is the go to practice
- Labels and inputs
	- still inner text but looks at inner text of label so need to link them correctly
		- htmlFor on label
		- id on input
	- ex: ![[Pasted image 20240610102601.png]]
	- ![[Pasted image 20240610102642.png]]

- button with icon and no text
	- ![[Pasted image 20240610103202.png]]
	- ![[Pasted image 20240610103233.png]]