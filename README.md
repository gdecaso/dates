# dates
Common dates utilities.

# Spanish date format for day of year
The method `DateUtils.getDateFromDayNumber(day, isLeapYear)` returns Spanish date format for a day of the year.
```
System.Out.println(DateUtils.getDateFromDayNumber(60, false));
// Prints "1 de marzo"

System.Out.println(DateUtils.getDateFromDayNumber(60, true));
// Prints "29 de febrero"
```

# Jar building
Gradle is recommended for jar building. Command
```
$ gradle build
```
Builds date.jar in build/lib directory.

Also, you can check tests and code coverage with `gradle test` and `gradle jacocoTestReport` commands. Reports are created in build/reports folder.

# Executable
Command
```
java -cp dates.jar net.dates.SpanishDate 322 false
```
Prints
```
18 de noviembre
```



