# Auto Scaling Project

This project presents a simple auto scaling system using a local Ubuntu virtual machine and AWS.

## How it works

* A Python script will monitor the CPU usage
* If the usage exceeds 75%, a deployment script will run
* The deployment script will simulate a deployment to a cloud

## Files

* monitor.py → CPU usage script
* deploy_to_cloud.sh → Deployment simulation

## How to run

python3 monitor.py
