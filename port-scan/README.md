## port-scan

Testing the accessibility of machine ports based on a list of addresses specified in a file using TCP.  

### example

```
> port-scan.sh example.txt

OK: 10.0.1.1 -> 8080
OK: google.com -> 444
ERROR: google.com -> 80
```