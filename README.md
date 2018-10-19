# Ant-Thony

`Ant-Thony` is a Python script which receives as input a file where each lines represents a task to be executed in the terminal.

Depending on the number of CPU cores specified with the `-c` flag, `Ant-Thony` will call his ant-buddies to do the job for him.

## Example

```bash
$ python ant_thony.py example/list
```

Output:

```
[Ant-Thony] WARNING: Number of cores has not been specified or it is incorrect. Using all available cores.
[Ant-Thony] INFO: Ant-Thony will use 4 cores
[Ant-Thony] INFO: Ant-1 ready with 1 tasks
[Ant-Thony] INFO: Ant-2 ready with 1 tasks
[Ant-Thony] INFO: Ant-3 ready with 1 tasks
[Ant-Thony] INFO: Ant-4 ready with 0 tasks
[Ant-Thony] INFO: Swarming!
[Ant-Thony] INFO: Ant-4 going back to the nest
[Ant-Thony] INFO: Ant-1 going back to the nest
[Ant-Thony] INFO: Ant-2 going back to the nest
[Ant-Thony] INFO: Ant-3 going back to the nest
[Ant-Thony] INFO: 3 tasks done
[Ant-Thony] INFO: All ants back to the nest
```

