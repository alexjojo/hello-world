//這邊以C1000(208.4、208.5、209.249這三台為例子)
FAB-209.249>enable
Password:
FAB-209.249#configure terminal
Enter configuration commands, one per line.  End with CNTL/Z.
FAB-209.249(config)#interface GigabitEthernet 3/0/44
FAB-209.249(config-if)#shutdown        //關閉GigabitEthernet 3/0/44 這個port
FAB-209.249(config-if)#no shutdown     //開啟GigabitEthernet 3/0/44 這個port
