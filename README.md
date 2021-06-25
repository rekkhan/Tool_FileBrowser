# Tool_FileBrowser
## What is it
Browse files in a path that contains the curly braces "{ }". Cpp doesn't seem to support it.

This one is written mainly for ROOT users.
## How to use?
1. Include it in your c/cpp code.
2. The return value is vector<string>, so do somthing like:
  
  ```c
  vector<string>  mypaths = fileBrowser (path_template, file_extension)
  ```
  
3. The arguments can be either std::string or ROOT::TString.
