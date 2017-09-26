# instance-probe

Instance-probe is a set of tools used to gather performance-related information
from servers when troubleshooting problems.

## Usage

Clone the repository onto the server in question:

```
git clone https://github.com/watsonian/instance-probe.git
```

To start gathering data, run the `gather-start` script:

```
./instance-probe/bin/gather-start
```

To stop gathering data, run the `gather-stop` script:

```
./instance-probe/bin/gather-stop
```

All gathered data will be in the `samples/` directory:

```
~ $ ls instance-probe/samples
diskstats-samples.txt  processes-samples.txt
```
