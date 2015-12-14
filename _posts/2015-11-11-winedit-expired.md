--- 
published: true
title: Get Rid of WinEdit Expired Problem
layout: post
author: Long
category: technical articles
tags: 
- software
- winedit

---

## Find Configuration File "Exit.edt"

options -> options interfaces ... -> Advanced Configuration ... -> Event Handlers -> Exit

the file looks like this:


~~~
// WinEdt Exit (Cleanup) Macro
 
   PushTagsandRegisters;
 
 //  CloseAppl("YAP");         // Close YAP if running?
 //  CloseAppl("Complete");    // Close Complete Wizard if running?
 
 // Remove Local ini and edt files if they are empty or the same as global
 // Users probably forget to do this before upgrading
 // so it is best to keep it tidy as we go...
 
 Exe('%b\Config\Cleanup.edt');
 
 PopTagsandRegisters;
 
 End; 
~~~


## Add Following Sentence Just Before **"End;"** 

    RegDeleteValue('HKEY_CURRENT_USER', 'Software\WinEdt 9', 'Inst');


## Close WinEdit and Reopen





  


