# binary console like in movies
for linux you need to run this before starting:

Microsoft Repo hinzufügen
wget -q https://packages.microsoft.com/config/ubuntu/22.04/packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo apt update
sudo apt install -y powershell
sudo ln -s /usr/bin/pwsh /usr/bin/powershell
