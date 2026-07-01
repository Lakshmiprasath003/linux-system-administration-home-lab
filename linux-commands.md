# Linux Commands (Home Lab Practice)

# --- File Operations ---
# list files in directory
ls

# current working directory
pwd

# change directory
cd folder_name

# create folder
mkdir test_folder

# create empty file
touch file.txt

# copy file
cp file1 file2

# move or rename file
mv oldname newname

# delete file
rm file.txt


# --- User Management ---
# add new user
sudo adduser user1

# create group
sudo groupadd developers

# add user to group
sudo usermod -aG developers user1


# --- Permissions ---
# change permissions
chmod 755 file.txt

# change ownership
sudo chown user:user file.txt


# --- SSH ---
# install ssh
sudo apt install openssh-server

# start ssh service
sudo service ssh start

# connect via ssh
ssh user@localhost


# --- Samba ---
# install samba
sudo apt install samba

# restart samba
sudo service smbd restart
