`Alt-F` jump a word forward   
`Alt-B` jump a word backwards    
`Ctrl-A` jump to start of line  
`Ctrl-E` jump to end of line   
`Ctrl-K` kill line forwards  
`Ctrl-U` kill line backwards   
`Ctrl-W` kill backwards by one word  
`Ctrl-Y` yank last action 

`A` enter Vim insert mode  
`ESC :WQ` write and quit Vim  
`:Q` quit Vim without saving  

`less +F filename.txt` read file from end without fully loading...  
`Ctrl-C` unbind from tail to scroll backwards  
`q` to exit  

`TAB TAB` get possible suggestions  

`Ctrl-X-E` open current shell line in editor, quitting editor runs commands  

`reset` like clear but can fix issues  

`Ctrl-R` reverse search history (recursive)
`Ctrl-G` escape reverse search and preserve input

Here document example:
```
curl http://localhost:8080/invocations -H "Content-Type:application/json" \
-d @- << EOF
{
    "key-1": "value-1",
    "key-2": "value-2"
}
EOF
```
 

