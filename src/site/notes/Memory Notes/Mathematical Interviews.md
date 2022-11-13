```dataview Questions
TABLE WITHOUT ID file.link AS Questions
WHERE contains(this.file.inlinks, file.link) 
AND !contains(file.name, "Interview Techniques")
AND !contains(file.name, "Digital Garden Homepage")
SORT file.name
```