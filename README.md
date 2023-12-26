# filectrl
File Controller

## Get Controller
```python
import filectrl
fctrl = filectrl.get_controller()
```
Parameters:  
write_type (filectrl.WriteType): Text, Data (default: .Text)  
data_separator (str): write_type == filectrl.WriteType.Data (default: ',')  
file_name (str): log file name. (default: ''; project directory name)  
file_type (str): log file extension name. (default: 'log')  
logging_path (str): logging path (default: '.')  
backup_path (str): Backup path for logged file. (default: './logs')\n

## Write
```python
fctrl.write("Hello, world!")
```