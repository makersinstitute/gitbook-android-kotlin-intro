#### Membandingkan Java dengan Kotlin

Ketika kita menggunakan [https://try.kotlinlang.org](https://try.kotlinlang.org) dan membuat sebuah model `Person` 

Berikut adalah perbandingan Java dengan Kotlin

```java
package com.example.lotus.garudav3;

public class Person {
    private String name;
    private int age;

    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}
```

```kotlin
package com.example.lotus.garudav3

class Person(name:String, age:Int) {
  var name:String
  var age:Int = 0
  init{
    this.name = name
    this.age = age
  }
}
```



