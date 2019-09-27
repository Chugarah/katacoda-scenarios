# Update Ubuntu

First task is to update the system, that includes the local
database of av available packages.

1. `sudo apt update`{{execute}}
2. `sudo apt upgrade -y`{{execute}}

During the process it will ask you about Libssl1.1:amd64 restart the serice. Just select "Yes"

Notice in step 2 how I added "-y" to accsept and update
packages for us. Be patient while the update is being processed
