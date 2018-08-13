### ANMedia feeder - cleaning up disk

`ssh anmedia-feeder`

`df -h` returns disk status)

`du -sh * | sort -h`   (tells us the biggest directories)

`rm an-media-thread-dump-201804*` (deletes everything in e.g. april 2018 - safe to do up to the last 7 days)

Can also look for log files e.g appnexas stuff

__or__ use this command to delete from the e.g. anm2/data dir:
`find /mnt/anm2/data -type f -mmin +720 -exec rm {} +`


### ANM Audiece Checks 

`ssh anmedia-feeder`

`lein repl :connect localhost:4001` (after openining a new terminal tab)

`(use 'controller.repl)`

copy output from logs


### RSA ID invalid format

`ssh-add -K ~/.ssh/id_rsa`
