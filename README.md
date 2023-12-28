AT17 - 04/12/2023


### Note_Zero: làm y như thầy hướng dẫn là được =))

Note 1: Khi tạo mô hình, ping 2 con winSV với win10 Client thì bình thường, còn muốn ping Ubuntu sang Win thì phải mở firewall win ra bằng command:

`netsh advfirewall firewall add rule name="ICMP Allow incoming V4 echo request" protocol=icmpv4:8,any  dir=in action=allow`
