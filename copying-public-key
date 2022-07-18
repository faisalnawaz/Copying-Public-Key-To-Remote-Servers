#!/bin/bash

ip_list=(192.168.0.113 192.168.0.115)

for ip in ${ip_list[@]};
do
	echo "******************$ip********************" >> password_change_ip_list_confirmation.txt
	echo "Here" >> password_change_ip_list_confirmation.txt
	sshpass -p "" ssh -t root@$ip 'echo "PASTE KEY HERE" >> /root/.ssh/authorized_keys'
	echo "Here" >> password_change_ip_list_confirmation.txt
done
