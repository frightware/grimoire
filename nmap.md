# nmap
## Network Mapper

### Examples:
For most cases a simple enumeration can be done as follows.
```markdown
nmap -F -sV $m0
```

Some hosts may have ICMP disabled. Many Windows devices are configured like this.
```markdown
nmap -Pn -F -sV $m0
```

A full port scan excluding the upper dynamic range. Includes all Well-Known and Registered ports.
```markdown
nmap -p-49151 $m0
```
