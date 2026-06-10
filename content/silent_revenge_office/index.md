```dataview
TABLE 
	title as "Название",
	choice(completion=0,"🟥",
		choice(completion=1,"🟨","🟩")) as "Завершение"
FROM "content/silent_revenge_office/main_story/_headers"
```