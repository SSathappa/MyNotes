# Create windows service using power shell command
 
## create service
   ```sc.exe create "service name" binpath= "..\app.exe" start= auto```

## add description
   ```sc.exe description "service name" "This is the description of the service.."```
