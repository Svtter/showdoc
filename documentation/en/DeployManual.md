﻿### Introduction 

 About ShowDoc , Please refer to [../../README.md](README.md)
 
### Environment dependence

 - Required environment
  
  `PHP5.3 or  above version ` ,`php-gd`,`php-pdo`
 
### Install and configure

- #### New installation
 
 - If you are familiar with the command line, you can install ShowDoc [by Composer](ByComposer.md "by Composer").
  Or manually download the code from https://github.com/star7th/showdoc/releases
 
 - Make these writable
  
       `/install`, `/Application/Runtime ` ,`/Public/Uploads`,`/Sqlite`,`/Sqlite/showdoc.db.php`
   
 - Windows sever
    
   Please entable `extension=php_sqlite.dll` ，`extension=php_pdo_sqlite.dll`and `php_mbstring.dll` in `php.ini` . Ignore it if you are on Linux.
 
 - Run installation
 
     `http://your-domain.com/install/`
   
 -  Default user : showdoc(password:123456)
   
- #### Upgrade 

 - If you are familiar with the command line, you can update ShowDoc [by Composer](http://www.showdoc.cc/help-en?page_id=32344 "by Composer").
  Or manually download the code from https://github.com/star7th/showdoc/releases
 - Backup your codes
 - Dowload new codes and decompression it to a new directory.Copy `/Sqlite/*` and `/Public/Uploads/*` from old directory to new directory
 
 - Open `http://your-domain.com/index.php?s=/home/update/db`  in your brown to update database 
 
 