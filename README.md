# Mvision Project by MFEC System Engineer
  Mvision project is a project that involves monitoring vSphere from VMWare to observe its various operations and send notifications in case of abnormal activity. The project includes the use of Grafana, InfluxDB, and Telegraf for monitoring purposes.
## Required
- [Docker Server Engine](https://docs.docker.com/engine/install/)
## Installing Docker Compose
First, confirm the latest version available in their [releases](https://github.com/docker/compose/releases) page. At the time of this writing, the most current stable version is `2.16.0`.

Download the binary file from the project’s GitHub page.
```bash
curl -L "https://github.com/docker/compose/releases/download/2.16.0/docker-compose-$(uname -s)-$(uname -m)" -o docker-compose
```
After the binary file is downloaded, move it to the `/usr/local/bin` folder, and then make it executable.
```bash
sudo mv docker-compose /usr/local/bin && sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose 
```
To verify that the installation was successful, you can run.
```bash
docker-compose --version
```
## Getting Started
To clone a git repository, you need to enter `sudo` mode first.
```bash
git clone https://github.com/IamNattawat/mvision_project.git
```
Navigate to the project directory.
```bash
cd mvision_project
```
You need to change the permission to `add_grafana.sh` and `add_vSphere.sh` file.
```bash
chmod 700 add_grafana.sh add_vSphere.sh
```
Command for installing Grafana Dashboard.
```bash
./add_grafana.sh
```
Command for setup add_vSphere.
```bash
./add_vSphere.sh
```
![Logo](https://user-images.githubusercontent.com/64506580/159311466-f720a877-6c76-403a-904d-134addbd6a86.png)
