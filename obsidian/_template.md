<%* var fileDate = moment(tp.file.title, "DD.MM.YYYY");-%>
<%* function month() { 
	let fileDateNum = fileDate.date(); 
	let numDays = fileDate.daysInMonth(); 
	tR += tp.user.makeProgressBar(fileDateNum, numDays, size=numDays, filledChar = "█", unFilledChar = "◽", label="Прохождение месяца"); 
	} 
	month(); 
-%> 
<%* function year() { 
	let dayNum = fileDate.dayOfYear(); 
	tR += tp.user.makeProgressBar(dayNum, 365, size=29,filledChar = "█", unFilledChar = "◽", label="Прохождение года"); 
	} 
	year(); 
%>



> [!Info] Shortcuts
> [💼 Work](_Tasks%20summary.md) [☕️Home](_start%20here.md)
> [[<% tp.date.now("DD.MM.YYYY", -1, tp.file.title, "DD.MM.YYYY") %>|⏪Yesterday]] [[<% tp.date.now("DD.MM.YYYY", +1, tp.file.title, "DD.MM.YYYY") %>|⏩Tomorrow]] [[y.disk/_Monthly/<% fileDate.format("YYYY.MM") %>|This month]] [[y.disk/_Monthly/<% fileDate.add(+1, 'month').format("YYYY.MM") %>|Next month]] 

- [ ] Проверить TickTick
- [ ] Проверить почту
- [ ] Проверить запросы на мерж

## Текущие задачи
![Current tasks](Current%20tasks.md)

## Сделано за день


## Notes

