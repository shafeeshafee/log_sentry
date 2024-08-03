### Give exec rights to `analyze.log.sh` & `auth_log_creation.sh`

```
chmod +x auth_log_creation.sh
chmod +x analyze_log.sh
```

### Open cron job editor

```
crontab -e
```

### Run the script daily before the day starts. An example might be like this:

```
0 6 * * * /home/ubuntu/scripts/analyze-log-files-with-bash/analyze_log.sh
```
