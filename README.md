<img src="single.jpg" width=480 height=270><img src="multiple.jpg" width=480 height=270>
# Zabbix_use_multiple_application
Use multiple application name in Data Overview widget

- In Zabbix 5.0.x haven't multiple select application at Data Overview widget.
I changed code at **"/usr/share/zabbix/include/items.inc.php"**
and now you can display some applications separated by **","**

-- You can yourself modifide code or download prepared file
-- Look at file "items.inc.php" in sub directories to understand how modifide file

To Debugging, uncomment lines with **"error_log"**
Debbug messages you can read at **"/var/log/{httpd|nginx}/error_log"**
