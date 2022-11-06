# Overdue
```tasks
(due before today) AND (not done)
sort by priority
```

# Due Today 
```tasks
due on today
sort by priority
```

# Today
```tasks
((has start date) AND (starts before today) AND (not done)) OR ((has start date) AND (starts on today))
sort by priority
```

# Due in 1 week
```tasks
not done
due before in 7 days
tags do not include #followup 
sort by due
sort by priority
```

# Nudges / Followups
```tasks
(no due date) OR ((due before in 3 days) AND (not done))
tags include #followup 
sort by status
sort by due
```
