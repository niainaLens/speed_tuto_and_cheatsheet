# Speed tuto & cheat sheet

Common usages of tools/ software/ services/ applications.

## License

GNU GENERAL PUBLIC LICENSE Version 3

## Contributing

1. Fork it

2. File formatting

   - file naming: 

   ```
   main_category/sub_category/software_[instruction].txt
   ```

   ex:

   ```
   scm/git/git_github_install_and_usage.txt
   ```

   - content formating

   ```
   --------- MAJOR PART I ---------
   
   --- Minor part A
   
   # instruction a
   	$ command-1
       
       	-v (--verbose): parameter explanation
       	
   # instruction b
   	
   	Sub-instruction b'
   		$ command-1
   	
   	Sub-instruction b"
   		$ command-2
   
   --- Minor part B
   
   # instruction a
   	$ command-1
   
   --------- MAJOR PART II ---------
   
   # instruction a
   	$ command-1
   		"
   			on-screen
   			output
   		"
   
   ```

   ex:

   ```
   --------- INSTALL ---------
   
   --- for debian
   
   # install
   	
   	Install via apt
   		$ sudo apt install git
   	
   	Intall via deb package
   		$ sudo dpkg -i git.deb
   
   --- for centOS
   
   # install
   	$ sudo yum install git
   
   --------- USAGE ---------
   
   # view commit history
       $ git log
       "
       commit 679930eb6866999f510b6027a67caaad5c5321a1
       Author: niainalens <niainalens@gmail.com>
       Date:   Thu May 2 17:22:50 2019 +0300
   
           adding file test
       "
   
           -p: more details
           --stat: less details
   ```

   

## Author Information

by Niaina Lens.