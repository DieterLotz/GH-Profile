# Profile

<div align="center">
  <img src="./assets/signals.gif" align="centre" width="50%" height="50%"/>
</div>

### About me :memo:

```js
  const profile = {
    name : 'Dieter',
    surname : 'Lötz',
    age : 24 💫,
    location : 'Cape Town, South Africa 📌',
    likes : [
      'music 🎧',
      'gaming 🎮', 
      'gyming 💪',
      'outdoors 🌳🌊',
      'programming ☕',
      'space exploration 🌍📡'
    ],
    dislikes : [
      '💩 code'
    ]    
  };
```

### Background :man_technologist: :mag:

#### Tech Stacks

> - Frontend: React.js, Angular :rocket:
> - Styling: CSS, SCSS :crystal_ball: :sewing_needle:
> - Backend: C# / .NET :globe_with_meridians:
> - Databases: Microsoft SQL Server, Postgres SQL :elephant:
> - Development Platform: Windows :computer:
> - Other: Docker :whale:

#### Education :open_book:

```cs

public static void Main(args string[]) {

 var qualifications = new List<Qualification> [
    new Qualification {
      Title = "AWS Developer Associate Certificate",
      Institution = "Amazon Web Services",
      IsCompleted = false,
    },
    new Qualification {
      Title = "National Diploma: Electrical Engineering",
      Institution = "Cape Peninsula University of Technology",
      IsCompleted = true,
      YearCompleted = 2020
    }
  ];

 var tertiaryEducation = new TertiaryEducation {
  Qualifications = qualifications
  }
};
}
  
public class TertiaryEducation {
  public IList<Qualification> Qualifications {get; set;}
}

public class Qualification {
  public string Title {get; set;}
  public string Institution {get; set;}
  public bool IsCompleted {get; set;}
  public int? YearCompleted {get; set;}
}
```
