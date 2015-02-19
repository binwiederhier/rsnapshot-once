# rsnapshot-once

rsnapshot-once is a wrapper for rsnapshot to ensure that daily, weekly and monthly tasks are run only once in the respective time period, i.e. it ensures that ‘weekly’ backups are executed only once a week, regardless how often rsnapshot-once is called. rsnapshot-once accepts the same parameters as rsnapshot and uses the same config file. No additional configuration is needed.

For more details check out [my blog post](http://blog.philippheckel.com/2013/06/28/script-run-rsnapshot-backups-only-once-and-rollback-failed-backups-using-rsnapshot-once/).
