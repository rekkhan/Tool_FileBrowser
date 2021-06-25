# Tool_FileBrowser
## What is it
A utility that browses files from a given path that may contain the curly braces "{ }", return the list of files as a vector<string>

Written mainly for ROOT users. People using TreeReader can use this package as TreeReader supports vector<string> as argument.
## How to use?
1. Include it in your c/cpp code.
2. The return value is vector<string>, so do somthing like:
  
  ```
  vector<string>  mypaths = fileBrowser (path_template, file_extension)
  ```
  
3. The arguments can be either std::string or ROOT::TString.
