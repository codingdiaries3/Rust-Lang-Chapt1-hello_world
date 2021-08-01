Going through the [rust lang book](https://doc.rust-lang.org/stable/book/ch01-02-hello-world.html
)

### Notes
1. To run a rust program 
     - First compile using 
     ``` 
     rustc nameOfFileYouWantToCompile.rs
     ```

      With nested files use 
     ```
     rustc ./foldername/foldername/file.rs
     ```
     - Then execute using
     ```
     ./nameOfFile.exe
     ```
     note: For windows add '.exe' and for linux or macOS exclude '.exe'

2. The "!" calls a rust macro. Without the exclamation point you're calling the function
