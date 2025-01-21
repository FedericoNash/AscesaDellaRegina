---
NoteType: Junk
key: value
key2: value2
key3: [one, two, three]
key4:
- four
- five
- six
alias: NoteName1, NoteName2, Fred, Bob, Goblin
tags: Tag4, Tag5
---

## Dataview
 `=this.key2`


```dataview
list from #Tag4
where NoteType = "Junk"
```

```dataview
table key, key2, key3, key4
from #Tag5
```


