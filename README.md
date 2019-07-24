# mac-mru
A Easy and Fast Forensic Tool for MRU Files.  

# Prerequisite
- Python 3

# How to use
You must specify options.  
- `-r` : root directory to search target files.  
- `-o` : output directory to write the result.
```
$ python app.py -r / -o ./out
$ cat ./out/mru_parsed.txt
```

<details>
<summary>Result</summary>

```
==========================================================================================
/Users/01011789/Library/Application Support/com.apple.spotlight.Shortcuts
==========================================================================================

******************************
display_name : 連絡先
lastUsed_timestamp : 2019-01-10 08:29:27
url : file:///Applications/Contacts.app/

==========================================================================================
/Users/01011789/Library/Application Support/com.apple.sharedfilelist/com.apple.LSSharedFileList.RecentApplications.sfl
==========================================================================================

******************************
creation_date : 2019-03-26 02:03:14+00:00
file_path : Applications/Sublime Text.app
creator : None
creator_UID : None

******************************
creation_date : 2017-01-07 08:00:00+00:00
file_path : Applications/Microsoft Word.app
creator : None
creator_UID : None

******************************
creation_date : 2016-10-22 21:31:55+00:00
file_path : Applications/Skitch.app
creator : None
creator_UID : None

******************************
creation_date : 2015-11-11 22:11:07+00:00
file_path : Applications/Xcode.app
creator : None
creator_UID : None

******************************
creation_date : 2015-10-24 00:37:09+00:00
file_path : Applications/Utilities/Terminal.app
creator : None
creator_UID : None

******************************
creation_date : 2018-12-10 18:15:13+00:00
file_path : Applications/Self_Service.app
creator : None
creator_UID : None

******************************
creation_date : 2015-09-18 04:52:42+00:00
file_path : Applications/Utilities/Activity Monitor.app
creator : None
creator_UID : None

******************************
creation_date : 2018-11-21 06:29:44+00:00
file_path : Applications/VMware Fusion.app
creator : None
creator_UID : None

******************************
creation_date : 2017-01-07 08:00:00+00:00
file_path : Applications/Microsoft PowerPoint.app
creator : None
creator_UID : None
```
</details>

# Reference
This tool using these tools internally.
- [macMRU-Parser](https://github.com/mac4n6/macMRU-Parser)
- [mac_alias](https://github.com/al45tair/mac_alias)
- [ccl-bplist](https://github.com/cclgroupltd/ccl-bplist)
