This schedule instructs GitHub Actions to run the workflow every day at 20:00 (8:00 PM) UTC. 
The five fields in the cron expression represent minute hour day-of-month month day-of-week, so 0 20 * * * means 
“run at minute 0 of the 20th hour, on every day of every month, regardless of day of week.” 
Note GitHub Actions uses UTC by default.
