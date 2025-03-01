######################################################################
$ bin/zookeeper-server-start.sh config/zookeeper.properties
######################################################################


INFO Reading configuration from: config/zookeeper.properties (org.apache.zookeeper.server.quorum.QuorumPeerConfig)WARN config/zookeeper.properties is relative. Prepend ./ to indicate that you're sure! (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO clientPortAddress is 0.0.0.0:2181 (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO secureClientPort is not set (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO observerMasterPort is not set (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO metricsProvider.className is org.apache.zookeeper.metrics.impl.DefaultMetricsProvider (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO autopurge.snapRetainCount set to 3 (org.apache.zookeeper.server.DatadirCleanupManager)
INFO autopurge.purgeInterval set to 0 (org.apache.zookeeper.server.DatadirCleanupManager)
INFO Purge task is not scheduled. (org.apache.zookeeper.server.DatadirCleanupManager)
WARN Either no config or no quorum defined in config, running in standalone mode (org.apache.zookeeper.server.quorum.QuorumPeerMain)
INFO Log4j 1.2 jmx support not found; jmx disabled. (org.apache.zookeeper.jmx.ManagedUtil)
INFO Reading configuration from: config/zookeeper.properties (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
WARN config/zookeeper.properties is relative. Prepend ./ to indicate that you're sure! (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO clientPortAddress is 0.0.0.0:2181 (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO secureClientPort is not set (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO observerMasterPort is not set (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO metricsProvider.className is org.apache.zookeeper.metrics.impl.DefaultMetricsProvider (org.apache.zookeeper.server.quorum.QuorumPeerConfig)
INFO Starting server (org.apache.zookeeper.server.ZooKeeperServerMain)
INFO ServerMetrics initialized with provider org.apache.zookeeper.metrics.impl.DefaultMetricsProvider@11dc3715 (org.apache.zookeeper.server.ServerMetrics)
INFO ACL digest algorithm is: SHA1 (org.apache.zookeeper.server.auth.DigestAuthenticationProvider)
INFO zookeeper.DigestAuthenticationProvider.enabled = true (org.apache.zookeeper.server.auth.DigestAuthenticationProvider)
INFO zookeeper.snapshot.trust.empty : false (org.apache.zookeeper.server.persistence.FileTxnSnapLog)
INFO  (org.apache.zookeeper.server.ZooKeeperServer)
INFO   ______                  _                                           (org.apache.zookeeper.server.ZooKeeperServer)
INFO  |___  /                 | |                                          (org.apache.zookeeper.server.ZooKeeperServer)
INFO     / /    ___     ___   | | __   ___    ___   _ __     ___   _ __    (org.apache.zookeeper.server.ZooKeeperServer)
INFO    / /    / _ \   / _ \  | |/ /  / _ \  / _ \ | '_ \   / _ \ | '__| (org.apache.zookeeper.server.ZooKeeperServer)
INFO   / /__  | (_) | | (_) | |   <  |  __/ |  __/ | |_) | |  __/ | |     (org.apache.zookeeper.server.ZooKeeperServer)
INFO  /_____|  \___/   \___/  |_|\_\  \___|  \___| | .__/   \___| |_| (org.apache.zookeeper.server.ZooKeeperServer)
INFO                                               | |                      (org.apache.zookeeper.server.ZooKeeperServer)
INFO                                               |_|                      (org.apache.zookeeper.server.ZooKeeperServer)
INFO  (org.apache.zookeeper.server.ZooKeeperServer)
INFO Server environment:zookeeper.version=3.8.3-6ad6d364c7c0bcf0de452d54ebefa3058098ab56, built on 2023-10-0510:34 UTC (org.apache.zookeeper.server.ZooKeeperServer)
INFO Server environment:host.name=815f25786085 (org.apache.zookeeper.server.ZooKeeperServer)
INFO Server environment:java.version=21.0.2 (org.apache.zookeeper.server.ZooKeeperServer)
INFO Server environment:java.vendor=Eclipse Adoptium (org.apache.zookeeper.server.ZooKeeperServer)
INFO Server environment:java.home=/opt/java/openjdk (org.apache.zookeeper.server.ZooKeeperServer)
INFO Server environment:java.class.path=/opt/kafka/bin/../libs/activation-1.1.1.jar:/opt/kafka/bin/../libs/aopalliance-repackaged-2.6.1.jar:1
INFO ZooKeeper Server Started



######################################################################
$ bin/kafka-server-start.sh config/server.properties
######################################################################
bin/kafka-server-start.sh: /usr/share/bashdb/bashdb-main.inc: No such file or directory
bin/kafka-server-start.sh: warning: cannot start debugger; debugging mode disabled
INFO Client environment:java.library.path=/opt/java/openjdk/lib/server:/opt/java/openjdk/lib:/opt/java/openjdk/../lib:/usr/java/packages/lib:/usr/lib64:/lib64:/lib:/usr/lib (org.apache.zookeeper.ZooKeeper)
INFO Client environment:java.io.tmpdir=/tmp (org.apache.zookeeper.ZooKeeper)
INFO Client environment:java.compiler=<NA> (org.apache.zookeeper.ZooKeeper)
INFO Client environment:os.name=Linux (org.apache.zookeeper.ZooKeeper)
INFO Client environment:os.arch=aarch64 (org.apache.zookeeper.ZooKeeper)
INFO Client environment:os.version=6.6.16-linuxkit (org.apache.zookeeper.ZooKeeper)
INFO Client environment:user.name=appuser (org.apache.zookeeper.ZooKeeper)
INFO Client environment:user.home=/home/appuser (org.apache.zookeeper.ZooKeeper)
INFO Client environment:user.dir=/opt/kafka (org.apache.zookeeper.ZooKeeper)
INFO Client environment:os.memory.free=982MB (org.apache.zookeeper.ZooKeeper)
INFO Client environment:os.memory.max=1024MB (org.apache.zookeeper.ZooKeeper)
INFO Client environment:os.memory.total=1024MB (org.apache.zookeeper.ZooKeeper)
INFO Initiating client connection, connectString=localhost:2181 sessionTimeout=18000 watcher=kafka.zookeeper.ZooKeeperClientconfig/server.properties1c852c0f (org.apache.zookeeper.ZooKeeper)
INFO jute.maxbuffer value is 4194304 Bytes (org.apache.zookeeper.ClientCnxnSocket)
INFO zookeeper.request.timeout value is 0. feature enabled=false (org.apache.zookeeper.ClientCnxn)
INFO [ZooKeeperClient Kafka server] Waiting until connected. (kafka.zookeeper.ZooKeeperClient)
INFO Opening socket connection to server localhost/127.0.0.1:2181. (org.apache.zookeeper.ClientCnxn)
INFO Socket connection established, initiating session, client: /127.0.0.1:46128, server: localhost/127.0.0.1:2181 (org.apache.zookeeper.ClientCnxn)
INFO Session establishment complete on server localhost/127.0.0.1:2181, session id = 0x10000684d2a0000, negotiated timeout = 18000 (org.apache.zookeeper.ClientCnxn)
INFO [ZooKeeperClient Kafka server] Connected. (kafka.zookeeper.ZooKeeperClient)
INFO Cluster ID = MOhKi6P7Rk2xzxgo0byD5Q (kafka.server.KafkaServer)
INFO KafkaConfig values:
        advertised.listeners = null
        alter.config.policy.class.name = null
        alter.log.dirs.replication.quota.window.num = 11
        alter.log.dirs.replication.quota.window.size.seconds = 1
        authorizer.class.name =
        auto.create.topics.enable = true
        auto.include.jmx.reporter = true
        auto.leader.rebalance.enable = true
        background.threads = 10
        broker.heartbeat.interval.ms = 2000
        broker.id = 0
        broker.id.generation.enable = true
        broker.rack = null
        broker.session.timeout.ms = 9000
        client.quota.callback.class = null
        compression.type = producer
        connection.failed.authentication.delay.ms = 100
        connections.max.idle.ms = 600000
        connections.max.reauth.ms = 0
        control.plane.listener.name = null
        controlled.shutdown.enable = true
        controlled.shutdown.max.retries = 3
        controlled.shutdown.retry.backoff.ms = 5000
        controller.listener.names = null
        controller.quorum.append.linger.ms = 25
        controller.quorum.election.backoff.max.ms = 1000
        controller.quorum.election.timeout.ms = 1000
        controller.quorum.fetch.timeout.ms = 2000
        controller.quorum.request.timeout.ms = 2000
        controller.quorum.retry.backoff.ms = 20
        controller.quorum.voters = []
        controller.quota.window.num = 11
        controller.quota.window.size.seconds = 1
        controller.socket.timeout.ms = 30000
        create.topic.policy.class.name = null
        default.replication.factor = 1
        delegation.token.expiry.check.interval.ms = 3600000
        delegation.token.expiry.time.ms = 86400000
        delegation.token.master.key = null
        delegation.token.max.lifetime.ms = 604800000
        delegation.token.secret.key = null
        delete.records.purgatory.purge.interval.requests = 1
        delete.topic.enable = true
        early.start.listeners = null
        eligible.leader.replicas.enable = false
        fetch.max.bytes = 57671680
        fetch.purgatory.purge.interval.requests = 1000
        group.consumer.assignors = [org.apache.kafka.coordinator.group.assignor.UniformAssignor, org.apache.kafka.coordinator.group.assignor.RangeAssignor]
        group.consumer.heartbeat.interval.ms = 5000
        group.consumer.max.heartbeat.interval.ms = 15000
        group.consumer.max.session.timeout.ms = 60000
        group.consumer.max.size = 2147483647
        group.consumer.min.heartbeat.interval.ms = 5000
        group.consumer.min.session.timeout.ms = 45000
        group.consumer.session.timeout.ms = 45000
        group.coordinator.new.enable = false
        group.coordinator.rebalance.protocols = [classic]
        group.coordinator.threads = 1
        group.initial.rebalance.delay.ms = 0
        group.max.session.timeout.ms = 1800000
        group.max.size = 2147483647
        group.min.session.timeout.ms = 6000
        initial.broker.registration.timeout.ms = 60000
        inter.broker.listener.name = null
        inter.broker.protocol.version = 3.7-IV4
        kafka.metrics.polling.interval.secs = 10
        kafka.metrics.reporters = []
        leader.imbalance.check.interval.seconds = 300
        leader.imbalance.per.broker.percentage = 10
        listener.security.protocol.map = PLAINTEXT:PLAINTEXT,SSL:SSL,SASL_PLAINTEXT:SASL_PLAINTEXT,SASL_SSL:SASL_SSL
        listeners = PLAINTEXT://:9092
        log.cleaner.backoff.ms = 15000
        log.cleaner.dedupe.buffer.size = 134217728
        log.cleaner.delete.retention.ms = 86400000
        log.cleaner.enable = true
        log.cleaner.io.buffer.load.factor = 0.9
        log.cleaner.io.buffer.size = 524288
        log.cleaner.io.max.bytes.per.second = 1.7976931348623157E308
        log.cleaner.max.compaction.lag.ms = 9223372036854775807
        log.cleaner.min.cleanable.ratio = 0.5
        log.cleaner.min.compaction.lag.ms = 0
        log.cleaner.threads = 1
        log.cleanup.policy = [delete]
        log.dir = /tmp/kafka-logs
        log.dirs = /tmp/kafka-logs
        log.flush.interval.messages = 9223372036854775807
        log.flush.interval.ms = null
        log.flush.offset.checkpoint.interval.ms = 60000
        log.flush.scheduler.interval.ms = 9223372036854775807
        log.flush.start.offset.checkpoint.interval.ms = 60000
        log.index.interval.bytes = 4096
        log.index.size.max.bytes = 10485760
        log.local.retention.bytes = -2
        log.local.retention.ms = -2
        log.message.downconversion.enable = true
        log.message.format.version = 3.0-IV1
        log.message.timestamp.after.max.ms = 9223372036854775807
        log.message.timestamp.before.max.ms = 9223372036854775807
        log.message.timestamp.difference.max.ms = 9223372036854775807
        log.message.timestamp.type = CreateTime
        log.preallocate = false
        log.retention.bytes = -1
        log.retention.check.interval.ms = 300000
        log.retention.hours = 168
        log.retention.minutes = null
        log.retention.ms = null
        log.roll.hours = 168
        log.roll.jitter.hours = 0
        log.roll.jitter.ms = null
        log.roll.ms = null
        log.segment.bytes = 1073741824
        log.segment.delete.delay.ms = 60000
        max.connection.creation.rate = 2147483647
        max.connections = 2147483647
        max.connections.per.ip = 2147483647
        max.connections.per.ip.overrides =
        max.incremental.fetch.session.cache.slots = 1000
        message.max.bytes = 1048588
        metadata.log.dir = null
        metadata.log.max.record.bytes.between.snapshots = 20971520
        metadata.log.max.snapshot.interval.ms = 3600000
        metadata.log.segment.bytes = 1073741824
        metadata.log.segment.min.bytes = 8388608
        metadata.log.segment.ms = 604800000
        metadata.max.idle.interval.ms = 500
        metadata.max.retention.bytes = 104857600
        metadata.max.retention.ms = 604800000
        metric.reporters = []
        metrics.num.samples = 2
        metrics.recording.level = INFO
        metrics.sample.window.ms = 30000
        min.insync.replicas = 1
        node.id = 0
        num.io.threads = 8
        num.network.threads = 3
        num.partitions = 1
        num.recovery.threads.per.data.dir = 1
        num.replica.alter.log.dirs.threads = null
        num.replica.fetchers = 1
        offset.metadata.max.bytes = 4096
        offsets.commit.required.acks = -1
        offsets.commit.timeout.ms = 5000
        offsets.load.buffer.size = 5242880
        offsets.retention.check.interval.ms = 600000
        offsets.retention.minutes = 10080
        offsets.topic.compression.codec = 0
        offsets.topic.num.partitions = 50
        offsets.topic.replication.factor = 1
        offsets.topic.segment.bytes = 104857600
        password.encoder.cipher.algorithm = AES/CBC/PKCS5Padding
        password.encoder.iterations = 4096
        password.encoder.key.length = 128
        password.encoder.keyfactory.algorithm = null
        password.encoder.old.secret = null
        password.encoder.secret = null
        principal.builder.class = class org.apache.kafka.common.security.authenticator.DefaultKafkaPrincipalBuilder
        process.roles = []
        producer.id.expiration.check.interval.ms = 600000
        producer.id.expiration.ms = 86400000
        producer.purgatory.purge.interval.requests = 1000
        queued.max.request.bytes = -1
        queued.max.requests = 500
        quota.window.num = 11
        quota.window.size.seconds = 1
        remote.log.index.file.cache.total.size.bytes = 1073741824
        remote.log.manager.task.interval.ms = 30000
        remote.log.manager.task.retry.backoff.max.ms = 30000
        remote.log.manager.task.retry.backoff.ms = 500
        remote.log.manager.task.retry.jitter = 0.2
        remote.log.manager.thread.pool.size = 10
        remote.log.metadata.custom.metadata.max.bytes = 128
        remote.log.metadata.manager.class.name = org.apache.kafka.server.log.remote.metadata.storage.TopicBasedRemoteLogMetadataManager
        remote.log.metadata.manager.class.path = null
        remote.log.metadata.manager.impl.prefix = rlmm.config.
        remote.log.metadata.manager.listener.name = null
        remote.log.reader.max.pending.tasks = 100
        remote.log.reader.threads = 10
        remote.log.storage.manager.class.name = null
        remote.log.storage.manager.class.path = null
        remote.log.storage.manager.impl.prefix = rsm.config.
        remote.log.storage.system.enable = false
        replica.fetch.backoff.ms = 1000
        replica.fetch.max.bytes = 1048576
        replica.fetch.min.bytes = 1
        replica.fetch.response.max.bytes = 10485760
        replica.fetch.wait.max.ms = 500
        replica.high.watermark.checkpoint.interval.ms = 5000
        replica.lag.time.max.ms = 30000
        replica.selector.class = null
        replica.socket.receive.buffer.bytes = 65536
        replica.socket.timeout.ms = 30000
        replication.quota.window.num = 11
        replication.quota.window.size.seconds = 1
        request.timeout.ms = 30000
        reserved.broker.max.id = 1000
        sasl.client.callback.handler.class = null
        sasl.enabled.mechanisms = [GSSAPI]
        sasl.jaas.config = null
        sasl.kerberos.kinit.cmd = /usr/bin/kinit
        sasl.kerberos.min.time.before.relogin = 60000
        sasl.kerberos.principal.to.local.rules = [DEFAULT]
        sasl.kerberos.service.name = null
        sasl.kerberos.ticket.renew.jitter = 0.05
        sasl.kerberos.ticket.renew.window.factor = 0.8
        sasl.login.callback.handler.class = null
        sasl.login.class = null
        sasl.login.connect.timeout.ms = null
        sasl.login.read.timeout.ms = null
        sasl.login.refresh.buffer.seconds = 300
        sasl.login.refresh.min.period.seconds = 60
        sasl.login.refresh.window.factor = 0.8
        sasl.login.refresh.window.jitter = 0.05
        sasl.login.retry.backoff.max.ms = 10000
        sasl.login.retry.backoff.ms = 100
        sasl.mechanism.controller.protocol = GSSAPI
        sasl.mechanism.inter.broker.protocol = GSSAPI
        sasl.oauthbearer.clock.skew.seconds = 30
        sasl.oauthbearer.expected.audience = null
        sasl.oauthbearer.expected.issuer = null
        sasl.oauthbearer.jwks.endpoint.refresh.ms = 3600000
        sasl.oauthbearer.jwks.endpoint.retry.backoff.max.ms = 10000
        sasl.oauthbearer.jwks.endpoint.retry.backoff.ms = 100
        sasl.oauthbearer.jwks.endpoint.url = null
        sasl.oauthbearer.scope.claim.name = scope
        sasl.oauthbearer.sub.claim.name = sub
        sasl.oauthbearer.token.endpoint.url = null
        sasl.server.callback.handler.class = null
        sasl.server.max.receive.size = 524288
        security.inter.broker.protocol = PLAINTEXT
        security.providers = null
        server.max.startup.time.ms = 9223372036854775807
        socket.connection.setup.timeout.max.ms = 30000
        socket.connection.setup.timeout.ms = 10000
        socket.listen.backlog.size = 50
        socket.receive.buffer.bytes = 102400
        socket.request.max.bytes = 104857600
        socket.send.buffer.bytes = 102400
        ssl.allow.dn.changes = false
        ssl.allow.san.changes = false
        ssl.cipher.suites = []
        ssl.client.auth = none
        ssl.enabled.protocols = [TLSv1.2, TLSv1.3]
        ssl.endpoint.identification.algorithm = https
        ssl.engine.factory.class = null
        ssl.key.password = null
        ssl.keymanager.algorithm = SunX509
        ssl.keystore.certificate.chain = null
        ssl.keystore.key = null
        ssl.keystore.location = null
        ssl.keystore.password = null
        ssl.keystore.type = JKS
        ssl.principal.mapping.rules = DEFAULT
        ssl.protocol = TLSv1.3
        ssl.provider = null
        ssl.secure.random.implementation = null
        ssl.trustmanager.algorithm = PKIX
        ssl.truststore.certificates = null
        ssl.truststore.location = null
        ssl.truststore.password = null
        ssl.truststore.type = JKS
        telemetry.max.bytes = 1048576
        transaction.abort.timed.out.transaction.cleanup.interval.ms = 10000
        transaction.max.timeout.ms = 900000
        transaction.partition.verification.enable = true
        transaction.remove.expired.transaction.cleanup.interval.ms = 3600000
        transaction.state.log.load.buffer.size = 5242880
        transaction.state.log.min.isr = 1
        transaction.state.log.num.partitions = 50
        transaction.state.log.replication.factor = 1
        transaction.state.log.segment.bytes = 104857600
        transactional.id.expiration.ms = 604800000
        unclean.leader.election.enable = false
        unstable.api.versions.enable = false
        unstable.metadata.versions.enable = false
        zookeeper.clientCnxnSocket = null
        zookeeper.connect = localhost:2181
        zookeeper.connection.timeout.ms = 18000
        zookeeper.max.in.flight.requests = 10
        zookeeper.metadata.migration.enable = false
        zookeeper.metadata.migration.min.batch.size = 200
        zookeeper.session.timeout.ms = 18000
        zookeeper.set.acl = false
        zookeeper.ssl.cipher.suites = null
        zookeeper.ssl.client.enable = false
        zookeeper.ssl.crl.enable = false
        zookeeper.ssl.enabled.protocols = null
        zookeeper.ssl.endpoint.identification.algorithm = HTTPS
        zookeeper.ssl.keystore.location = null
        zookeeper.ssl.keystore.password = null
        zookeeper.ssl.keystore.type = null
        zookeeper.ssl.ocsp.enable = false
        zookeeper.ssl.protocol = TLSv1.2
        zookeeper.ssl.truststore.location = null
        zookeeper.ssl.truststore.password = null
        zookeeper.ssl.truststore.type = null
 (kafka.server.KafkaConfig)
INFO [ThrottledChannelReaper-Fetch]: Starting (kafka.server.ClientQuotaManager)
INFO [ThrottledChannelReaper-Produce]: Starting (kafka.server.ClientQuotaManager)
INFO [ThrottledChannelReaper-Request]: Starting (kafka.server.ClientQuotaManager)
INFO [ThrottledChannelReaper-ControllerMutation]: Starting (kafka.server.ClientQuotaManager)
INFO Loading logs from log dirs ArraySeq(/tmp/kafka-logs) (kafka.log.LogManager)
INFO No logs found to be loaded in /tmp/kafka-logs (kafka.log.LogManager)
INFO Loaded 0 logs in 7ms (kafka.log.LogManager)
INFO Starting log cleanup with a period of 300000 ms. (kafka.log.LogManager)
INFO Starting log flusher with a default period of 9223372036854775807 ms. (kafka.log.LogManager)
INFO [kafka-log-cleaner-thread-0]: Starting (kafka.log.LogCleaner)
INFO [feature-zk-node-event-process-thread]: Starting (kafka.server.FinalizedFeatureChangeListener)
INFO [MetadataCache brokerId=0] Updated cache from existing None to latest Features(version=3.7-IV4, finalizedFeatures={}, finalizedFeaturesEpoch=0). (kafka.server.metadata.ZkMetadataCache)
INFO [zk-broker-0-to-controller-forwarding-channel-manager]: Starting (kafka.server.NodeToControllerRequestThread)
INFO Updated connection-accept-rate max connection creation rate to 2147483647 (kafka.network.ConnectionQuotas)
INFO [SocketServer listenerType=ZK_BROKER, nodeId=0] Created data-plane acceptor and processors for endpoint : ListenerName(PLAINTEXT) (kafka.network.SocketServer)
INFO [zk-broker-0-to-controller-alter-partition-channel-manager]: Starting (kafka.server.NodeToControllerRequestThread)
INFO [ExpirationReaper-0-Produce]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [ExpirationReaper-0-Fetch]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [ExpirationReaper-0-DeleteRecords]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [ExpirationReaper-0-ElectLeader]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [ExpirationReaper-0-RemoteFetch]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [LogDirFailureHandler]: Starting (kafka.server.ReplicaManager)
INFO [AddPartitionsToTxnSenderThread-0]: Starting (kafka.server.AddPartitionsToTxnManager)
INFO Creating /brokers/ids/0 (is it secure? false) (kafka.zk.KafkaZkClient)
INFO Stat of the created znode at /brokers/ids/0 is: 46,46,1717509311007,1717509311007,1,0,0,72058042009124864,208,0,46

INFO Registered broker 0 at path /brokers/ids/0 with addresses: PLAINTEXT://815f25786085:9092, czxid (broker epoch): 46 (kafka.zk.KafkaZkClient)
INFO [ExpirationReaper-0-topic]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [ExpirationReaper-0-Heartbeat]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [ExpirationReaper-0-Rebalance]: Starting (kafka.server.DelayedOperationPurgatory)
INFO [GroupCoordinator 0]: Starting up. (kafka.coordinator.group.GroupCoordinator)
INFO [GroupCoordinator 0]: Startup complete. (kafka.coordinator.group.GroupCoordinator)
INFO [TransactionCoordinator id=0] Starting up. (kafka.coordinator.transaction.TransactionCoordinator)
INFO [TxnMarkerSenderThread-0]: Starting (kafka.coordinator.transaction.TransactionMarkerChannelManager)
INFO [TransactionCoordinator id=0] Startup complete. (kafka.coordinator.transaction.TransactionCoordinator)
INFO [Controller id=0, targetBrokerId=0] Node 0 disconnected. (org.apache.kafka.clients.NetworkClient)
INFO [ExpirationReaper-0-AlterAcls]: Starting (kafka.server.DelayedOperationPurgatory)
WARN [Controller id=0, targetBrokerId=0] Connection to node 0 (815f25786085/172.17.0.2:9092) could not be established. Node may not be available. (org.apache.kafka.clients.NetworkClient)
INFO [Controller id=0, targetBrokerId=0] Client requested connection close from node 0 (org.apache.kafka.clients.NetworkClient)
INFO [/config/changes-event-process-thread]: Starting (kafka.common.ZkNodeChangeNotificationListener)
INFO [SocketServer listenerType=ZK_BROKER, nodeId=0] Enabling request processing. (kafka.network.SocketServer)
INFO Awaiting socket connections on 0.0.0.0:9092. (kafka.network.DataPlaneAcceptor)
INFO Kafka version: 3.7.0 (org.apache.kafka.common.utils.AppInfoParser)
INFO Kafka commitId: 2ae524ed625438c5 (org.apache.kafka.common.utils.AppInfoParser)
INFO Kafka startTimeMs: 1717509311104 (org.apache.kafka.common.utils.AppInfoParser)
INFO [KafkaServer id=0] started (kafka.server.KafkaServer)
INFO [zk-broker-0-to-controller-forwarding-channel-manager]: Recorded new controller, from now on will use node 815f25786085:9092 (id: 0 rack: null) (kafka.server.NodeToControllerRequestThread)
INFO [zk-broker-0-to-controller-alter-partition-channel-manager]: Recorded new controller, from now on will use node 815f25786085:9092 (id: 0 rack: null) (kafka.server.NodeToControllerRequestThread)
Kafka Server Started...
