![](https://github.com/95domy/android-pds20_3a/blob/master/doc/images/MECU_sprint1.png)

En el diagrama anterior hi apareixen referències a:
- AuthProvider
- BattleState
- QuestionLevel
- QuestionCategory

Tots aquests tipus són estructures de tipus 'ENUM' i són les següents:

### AuthProvider
```{java}
public enum AuthProvider {
    local,
    google,
    apple,
    github
}
```

### BattleState
```{java}
public enum BattleState {
    open,
    closed
}
```

### QuestionLevel
```{java}
public enum QuestionLevel {
    PRO,
    AMATEUR,
    NOOB
}
```

### QuestionCategory
```{java}
public enum QuestionCategory {
    MATH,
    ENGLISH,
    SPANISH,
    HISTORY,
    BIOGEO, //biology and geology
    PHYCHEM, // physics and chemistry
    OTHERS
}
```