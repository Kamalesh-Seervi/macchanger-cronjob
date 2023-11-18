<img width="807" alt="image" src="https://github.com/Kamalesh-Seervi/macchanger-cronjob/assets/107933310/444c8680-1e52-48d3-b6ce-79e8a40e58d2"># macchanger-cronjob
Changes Mac address of the system on every time of the reboot 

# Setup 
- Install macchanger
```
sudo apt install macchanger
```

## Script file 

- Clone the above code
- Make it executable file
```
chmod +x macchanger.sh
```

## Cronjob

- Type the below command to create a new job.
```
cronjob -e
```
- Type 1 if you want use nano editor or 2 to use vim.
- Now it will open a editor file go to the bottom of the file and type the below command to create a new job.(`@reboot <path of the script file>`)
```
@reboot /home/kali/Desktop/macchanger.sh
```
<img width="807" alt="image" src="https://github.com/Kamalesh-Seervi/macchanger-cronjob/assets/107933310/a6870d3d-3b6f-4b84-99d8-3255dc6a32cd">

