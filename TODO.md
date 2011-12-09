### reorg

* symlinks in cookbooks
  - users cookbook
  - infochimps_chef roles

* knife/bootstrap

* cluster_chef gem


### Cookbook attribute refresh:

                          | flip fixed | temujin9 checked |
                          +------------+------------------+
        cassandra	  |            |                  |
        ec2               |            |                  |
        elasticsearch	  |            |                  |
        firewall	  |            |                  |
        flume             |            |                  |
        ganglia           |            |                  |
        graphite	  |            |                  |
        hadoop_cluster	  |            |                  |
        hbase             |            |                  |
        hive              |            |                  |
        jenkins           |            |                  |
        jruby             |            |                  |
        nfs               |            |                  |
        nodejs            |            |                  |
        papertrail	  |            |                  |
        pig               |            |                  |
        redis             |            |                  |
        resque            |            |                  |
        Rstats            |            |                  |
        statsd            |            |                  |
        zookeeper	  |            |                  |
        # meta:
        install_from	  |            |                  |
        motd              |            |                  |
        mountable_volumes |            |                  |
        provides_service  |            |                  |
        # Need thinkin':
        big_package	  |            |                  |
        cluster_chef      |            |                  |


### std cookbooks

#### integration

* apt: has a dashboard at http://{hostname}:3142/report

### Cookbook Munger

* update to-from comments in attributes.rb