Linux Performance Commands

The following command lists all switched contexts by all cpus
```
sudo perf stat -e sched:sched_switch --all-cpus -I 1000
```
