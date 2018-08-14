# problem_had_met
this is a list of problem i had met

#1.
	Actual binding is of type [org.apache.logging.slf4j.Log4jLoggerFactory]
Exception in thread "main" java.lang.ExceptionInInitializerError

#2
	12647 [Thread-20-id_kafka_spout-executor[3 3]] INFO  o.a.s.k.ZkCoordinator - Task [1/1] Finished refreshing
14941 [ProcessThread(sid:0 cport:-1):] INFO  o.a.s.s.o.a.z.s.PrepRequestProcessor - Got user-level KeeperException when processing sessionid:0x1650ac79bb80010 
type:create cxid:0x3 zxid:0x3f txntype:-1 reqpath:n/a Error Path:/f-k-s/consumer-id Error:KeeperErrorCode = NoNode for /f-k-s/consumer-id

#3
	ERROR client.AsyncProcess: Failed to get region location 
org.apache.hadoop.hbase.exceptions.UnknownProtocolException: org.apache.hadoop.hbase.exceptions.UnknownProtocolException: Is this a pre-hbase-1.0.0 or asynchbase client? Client is invoking getClosestRowBefore removed in hbase-2.0.0 replaced by reverse Scan.
        at org.apache.hadoop.hbase.regionserver.RSRpcServices.get(RSRpcServices.java:2438)
        at org.apache.hadoop.hbase.shaded.protobuf.generated.ClientProtos$ClientService$2.callBlockingMethod(ClientProtos.java:41998)

#4
	Starting Hive Metastore Server
	MetaException(message:Version information not found in metastore. )