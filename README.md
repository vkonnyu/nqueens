# nqueens

Place N queens on an NxN chess board so that none of them attack each other (the classic n-queens problem). Additionally, please make sure that no three queens are in a straight line at ANY angle, so queens on A1, C2 and E3, despite not attacking each other, form a straight line at some angle.

## Execute with Gradle

Solve for 8 queens
```
gradle run
```

Solve for n queens (passing command line args requires Gradle 4.9)
```
gradle run --args="n"
```
