# Lab Report 3
---
### The command I choose is 	**grep**  
- **Option One**:  `grep -r`  
> Description: --**recursive**
              Read all files under each directory, recursively, following
              symbolic  links only if they are on the command line.  Note
              that if no file operand is given, grep searches the working
              directory. 
              [source](https://linuxcommand.org/lc3_man_pages/grep1.html)   
              
 **Example 1**  

   
   
 
 ```
 $ grep -r "Honolulu" ./
./travel_guides/berlitz1/HandRHawaii.txt:        Oahu (Including Honolulu)
./travel_guides/berlitz1/HandRHawaii.txt:        Aston Waikiki Sunset $$$ 229 Paoakalani Avenue, Honolulu, HI
./travel_guides/berlitz1/HandRHawaii.txt:        Halekulani $$$$ 2199 Kalia Road, Honolulu, HI 96815; Tel.
./travel_guides/berlitz1/HandRHawaii.txt:        Hilton Hawaiian Village $$$–$$$$ 2005 Kalia Road, Honolulu,
./travel_guides/berlitz1/HandRHawaii.txt:        Honolulu, HI 96815; Tel. (808) 923-1234 or (800) 233-1234; fax (808)
./travel_guides/berlitz1/HandRHawaii.txt:        half-hour drive of Honolulu. 387 rooms.
./travel_guides/berlitz1/HandRHawaii.txt:        Honolulu, HI 96816; Tel. (808) 739-8888 or (800) 367-2525; fax (808)
./travel_guides/berlitz1/HandRHawaii.txt:        Outrigger Reef $$$ 2169 Kalia Road, Honolulu, HI 96815; Tel.
./travel_guides/berlitz1/HandRHawaii.txt:        Pacific Beach Hotel $$$ 2490 Kalakaua Avenue,, Honolulu, HI
./travel_guides/berlitz1/HandRHawaii.txt:        Royal Hawaiian $$$$ 2259 Kalakaua Avenue, Honolulu, HI
./travel_guides/berlitz1/HandRHawaii.txt:        Honolulu, HI 96815; Tel. (808) 922-3111 or (800) 325-3535; fax (808)
./travel_guides/berlitz1/HandRHawaii.txt:        Honolulu, HI 96815; Tel. (808) 922-5811 or (800) 325-3535; fax (808)
./travel_guides/berlitz1/HandRHawaii.txt:        Sheraton Waikiki $$$–$$$$ 2255 Kalakaua Avenue, Honolulu,
./travel_guides/berlitz1/HistoryHawaii.txt:        church and the mission schools (which you can still visit in Honolulu)
./travel_guides/berlitz1/HistoryHawaii.txt:        Honolulu. The Calvinistic reforms were soon reversed when Kaahumanu
./travel_guides/berlitz1/HistoryHawaii.txt:        still be toured in Honolulu. He also legalized the hula, Hawaii’s
./travel_guides/berlitz1/HistoryHawaii.txt:        governor was Dole. Queen Liliuokalani lived out her life near Honolulu,
./travel_guides/berlitz1/WhatToHawaii.txt:        Midway. Lying some 1,100 miles northwest of Honolulu, Midway
 ```
**Explaination**: The command goes recursively through the directories and files under *writtern_2* and outputs the files that contains the string "Honolulu" followed with the sentence that contains this word. 

 **Example 2**
  ```
  $ grep -r "fdiujk" ./travel_guides
   ```
  **Explaination**: The command goes recursively through the directories and files under *travel_guides* to find files contains "fdiujk". Since no such file exists, the output is empty. 
 
 
 ---
 
 - **Option Two**:  `grep --color[=WHEN]` 
> Description  **--color**              
               Surround the matched (non-empty) strings,  matching  lines,
              context  lines, file names, line numbers, byte offsets, and
              separators (for fields and groups of  context  lines)  with
              escape  sequences to display them in color on the terminal.
              The  colors  are  defined  by  the   environment   variable
              GREP_COLORS.     The    deprecated   environment   variable
              GREP_COLOR is still supported, but  its  setting  does  not
              have priority.  WHEN is never, always, or auto.
              [source](https://linuxcommand.org/lc3_man_pages/grep1.html) 
                
                
 **Example 1**  

![alt text](https://i.ibb.co/tZB1b83/Screenshot-2023-02-12-182711.jpg)

**Explaination** :the command colors the matching string in  the file as output.
 
 
 **Example 2**
  
  ![alt text](https://i.ibb.co/1RMMT6N/Screenshot-2023-02-12-183955.jpg)

  **Explaination** :the command colors the matching number in  the file as output.
 
 --- 
 - **Option Three**:  `grep -c` 
 
> Description   **--count**
              Suppress normal output; instead print a count  of  matching
              lines  for  each  input  file.  With the -v, --invert-match
              option (see below), count non-matching lines.
              [source](https://linuxcommand.org/lc3_man_pages/grep1.html)   
              
 **Example 1**  
 ```  
 $ grep -c "Kalia" HandRHawaii.txt
      4     
```
**Explaination** : The command counts the number of lines in *HandRHawaii.txt* that contains the word "Kalia".
 
 **Example 2**
 ```
 $  grep -c "maniac" HandRHawaii.txt
    0 
```
**Explaination** : The command counts the number of lines in *HandRHawaii.txt* that contains the word "maniac" which is zero.

--- 
  - **Option Four**:  `grep -i` 
> Description --ignore-case
              Ignore  case  distinctions,  so that characters that differ
              only in case match each other.
                 [source](https://linuxcommand.org/lc3_man_pages/grep1.html)  
                              
  **Example 1**   
 ```
 $  grep -i "hong kong" HandRHongKong.txt
        Hong Kong has some of the most luxurious hotels in the
        limited room service, and a wide range of facilities. Hong Kong hotels
        arrangements, the Hong Kong Hotel Reservation Center at the
        indicate high-season rates in Hong Kong dollars, based on double
 ```
        
**Explaination**:The command catch the paragraph in *HandRHongKong.txt* that contains the string "hong kong" without being case sensitive and returns 
that paragraph as output.


 
 **Example 2**      
 ```   
 $ grep -i "hongkong" HandRHongKong.txt
 ```
 **Explaination**: The command catch the paragraph in *HandRHongKong.txt* that contains the string "hong kong" without being case sensitive but it's still space-sensitive. Since no such match is found, the output is empty. 
