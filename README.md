## [Project 24: Swift Strings](https://www.hackingwithswift.com/read/24/overview)
Written by [Paul Hudson](https://www.hackingwithswift.com/about)  ![twitter16](https://github.com/juliangyurov/PH-Project6a/assets/13259596/445c8ea0-65c4-4dba-8e1f-3f2750f0ef51)
  [@twostraws](https://twitter.com/twostraws)

**Description:** Dive deep into how strings work in Swift, and learn how to add formatting on top.

- Setting up

- Strings are not arrays

- Working with strings in Swift

- Formatting strings with `NSAttributedString`

- Wrap up


  
## [Review what you learned](https://www.hackingwithswift.com/review/hws/project-24-swift-strings)

**Challenge**

1. Create a String extension that adds a `withPrefix()` method. If the string already contains the prefix it should return itself; if it doesn’t contain the prefix, it should return itself with the prefix added. For example: "pet".withPrefix("car") should return “carpet”.

2. Create a String extension that adds an `isNumeric` property that returns true if the string holds any sort of number. Tip: creating a Double from a String is a failable initializer.
   
3. Create a String extension that adds a lines property that returns an array of all the lines in a string. So, “this\nis\na\ntest” should return an array with four elements.
