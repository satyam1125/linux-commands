# Linux Commands Notes (by satyam)

pwd        # Show current directory

ls         # List files
ls -a      # List all files (including hidden)

cd Documents   # Change directory to Documents
cd ..      # Move back one directory

mkdir satyam_folder   # Create directory

rmdir satyam_folder   # Remove empty directory

touch satyam.txt      # Create empty file

cat satyam.txt        # View file content

echo "Hello Satyam" >> satyam.txt   # Write text to file

nano satyam.txt       # Edit file with nano

cp satyam.txt satyam_copy.txt   # Copy file

mv satyam.txt satyam_old.txt    # Rename/Move file

rm satyam_copy.txt    # Delete file

clear     # Clear terminal screen

uname -a  # Show system information

date      # Show current date/time

cal       # Show calendar

man ls    # Manual/help for a command

# 🔹 User & Permission Management

whoami                # Show current user

id                    # Show user ID and groups

sudo su               # Switch to root user

adduser hacker        # Add a new user

passwd hacker         # Change password of user

chmod 755 satyam.sh   # Change permissions

chown root:root satyam.sh   # Change file ownership

# 🔹 Networking & Hacking Basics

ifconfig              # Show network interfaces (use ip a in new systems)

ip a                  # Show IP addresses

ping -c 4 google.com  # Send ping requests

netstat -tulnp        # Show active ports & services

ss -tuln              # Alternative to netstat

curl http://satyam.com   # Fetch website data

wget http://satyam.com/file.txt   # Download file

nmap -sV 127.0.0.1    # Scan local machine services

nc -lvp 4444          # Start netcat listener (backdoor test)

# 🔹 System Monitoring & Info

top                   # Show running processes

htop                  # Better process viewer (install if not available)

ps aux                # Show all processes

kill -9 1234          # Kill process with PID 1234

df -h                 # Show disk usage

du -sh *              # Show folder sizes

uptime                # Show system uptime

history               # Show command history
