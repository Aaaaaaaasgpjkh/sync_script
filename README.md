# Adding script to cron
- Specify file location in syn.sh

- Make syn.sh executable `chmod +x /home/username/syn.sh`

- Open crontab `crontab -e`

- Write task
  ```
  DISPLAY=:0
  * * * * * /home/username/syn.sh
  ```