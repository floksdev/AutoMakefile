# AutoMakefile
💻 | A Makefile generator script for your projects

***How to run it ?***

- Create a config file that contains all flags you want to add in your Makefile separate by a ';'

*For exemple the config file can contain the following rules :*

```
• source_filename;dependence1 dependence2. . .
(specify the full names of the files, from the header subfolder below)
• PROJECT_DIR;name_of_the_project_root_folder
• SOURCES_DIR;subfolder_containing_the_source_files
• HEADERS_DIR;subfolder_containing_the_header_files
• LIBS_DIR;subfolder_containing_librairies
• EXEC;executable_name
• CC;compilator_binary
• CFLAGS;compilation_flag1 compilation_flag1. . .
• LDFLAGS;linking_flag1 linking_flag2. .
```

⚠️ | The Makefile will be generate in the folder containing the config file 
