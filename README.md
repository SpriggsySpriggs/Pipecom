# Pipecom
Pipecom - Use pipes and stdhandles to read back console output! No more temp files!

Basic usage for returning back console output as a string only:
```vb
Print pipecom_lite("dir")
```

Usage for returning back stdout, stderr, and exit codes:
```vb
Dim As Long exit_code
Dim As String stdout, stderr
exit_code = pipecom("dir", stdout, stderr)
'print or manipulate values as you see fit
```
