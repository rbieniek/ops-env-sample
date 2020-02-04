# ops-dev-sample: Example project for demonstrating various operations support infrastructure components and patterns

## Included components

## Required preparations

### Install the local-persist docker volume driver
In order to avoid costly initialization operations, the example docker-compose.yml file makes use of the **local-persist** docker volume plugin.

For detailed installation instructions, please refer to this page [MatchbookLab/local-persist](https://github.com/MatchbookLab/local-persist)

### Change host system kernel settings
Adjust the maximum number of memory map areas a process may have by issuing
the `sudo sysctl -w vm.max_map_count=262144` comand
