# Mvision Project by MFEC System Engineer
  Mvision project is a project that involves monitoring vSphere from VMWare to observe its various operations and send notifications in case of abnormal activity. The project includes the use of Grafana, InfluxDB, and Telegraf for monitoring purposes.
## Required
- [Docker Server Engine](https://docs.docker.com/engine/install/)
## Installing Docker Compose
On Ubuntu OS you can run command.
```bash
apt install docker-compose
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
