rsyslog-to-logstash
===================

This is simple ansible play which setups rsyslogd forwarding to 
remote logstash.

Fell free to use, reuse and abuse it.

     ansible-playbook -i hosts.example 
     ansible-playbook -i hosts.example rsyslog_to_logstash.yml -v

