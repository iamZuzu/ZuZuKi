

> [!Ideas]
> 
>```dataview
TABLE file.day.weekyear AS Week, idea AS Ideas
FROM "0. INBOX/Journal/Daily"
WHERE Idea != null
>```



>[!achievements]
>
>```dataview
TABLE file.day.weekyear AS Week, Achievements
FROM "0. INBOX/Journal/Daily"
WHERE Achievements != null
>```


>[!motivation]
>
>```dataview
TABLE file.day.weekyear AS Week, Motivation
FROM "0. INBOX/Journal/Daily"
WHERE Motivation != null
>```


>[!gratitude]
>
>```dataview
TABLE file.day.weekyear AS Week, Gratitude
FROM "0. INBOX/Journal/Daily"
WHERE gratitude != null
>```


>[!highlights]
>
>```dataview
TABLE file.day.weekyear AS Week, highlights AS Highlights
FROM "0. INBOX/Journal/Daily"
WHERE highlights != null
>```

