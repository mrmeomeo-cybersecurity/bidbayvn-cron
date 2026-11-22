# bidbayvn-cron
Public scheduler for BidBayVN: a GitHub Actions workflow pings the cron
endpoints on https://bidbayvn.com every 5 minutes (emails), every 10 minutes
(payments) and once a day (daily). Requires one repo secret: CRON_SECRET.
