
This chapter lists the changes made to this document from the previous release.


![image](images/NoteSmall.jpg)***NOTE:*** *Please refer to the <a href="http://docs.hazelcast.org/docs/release-notes/" target="_blank">Release Notes</a> for the new features, enhancements and fixes performed for each Hazelcast IMDG release.*


|Chapter/Section|Description|
|:-------|:-----------|
|[Phone Home](/100_Preface/900_Phone_Home.md)|Added information related to the new environment variable `HZ_PHONE_HOME_ENABLED` for disabling phone homes. 
|[Consistency and Replication Model](/450_Consistency_and_Replication_Model.md)| Added as a new chapter to explain the full picture of Hazelcast's consistency model.
|[Configuration Pattern Matcher](/500_Understanding_Configuration/550_Configuration_Pattern_Matcher.md)| Added as a new section.
|[Dynamically Adding Configuration on a Cluster](/500_Understanding_Configuration/450_Dynamically_Adding_Data_Structure_Configuration_on_a_Cluster.md)|Added as a new section.
|[User Code Deployment](/04_Setting_Up_Clusters/07_User_Code_Deployment_-_BETA.md)|Added "Example for Member Filtering Members" as a new section to explain how to use the `provider-filter` element.
|[Client User Code Deployment](/04_Setting_Up_Clusters/07_Client_User_Code_Deployment_-_BETA.md)|Added as a new section.
|[Failure Detector Configuration](/600_Setting_Up_Clusters/1200_Failure_Detector_Configuration.md)| Added as a new section to explain Hazelcast's Deadline and Phi Accrual failure detectors.
|[Lock](/06_Distributed_Data_Structures/900_Lock.md)|Added "Lock vs. IMap.lock" as a new section.
|[Event Journal](/06_Distributed_Data_Structures/1700_Event_Journal.md)| Added as a new section to explain the event journal distributed data structure that stores the history of mutation actions on the data structures such as map or cache.
|[Entry Processor](/08_Distributed_Computing/03_Entry_Processor)|Added the new section "Entry Processor Optimization" explaining Offloadable and Readonly entry processors.|
|[Scoping to Join Clusters](/11_Hazelcast_JCache/05_Hazelcast_JCache_Extension-ICache/00_Scoping_to_Join_Clusters.md)|Enhanced the content to explain and give examples about the Hazelcast instance creations during cache manager starts (Hazelcast JCache).
|[Enabling Client TLS/SSL](/1600_Hazelcast_Clients/100_Java_Client/300_Configuration/100_Client_Network.md)|Added information related to mutual authentication.
|[Async Start and Reconnect Modes](/1600_Hazelcast_Clients/100_Java_Client/200_Getting_Started.md#page_AsyncStartandReconnectMode.html) and [Configuring Client Connection Strategy](/1600_Hazelcast_Clients/100_Java_Client/300_Configuration/750_Client_Connection_Strategy.md)| Added as new sections. Also added "Setting Outbound Ports" as a new section under [Client Network Configuration](/1600_Hazelcast_Clients/100_Java_Client/300_Configuration/100_Client_Network.md).
|[SSL](/18_Security/04_TLS-SSL.md)|Added the new sections "Authenticating Mutually" and "TLS/SSL Debugging".
|[Integrating with Spring](/1400_Integrated_Clustering/300_Integrating_with_Spring)| Added [Defining Timeouts for Cache Read Operation](/1400_Integrated_Clustering/300_Integrating_with_Spring/300_Adding_Caching_to_Spring.md) as a new section.
|[Management Center](/1900_Management/700_Management_Center.md)|Content has been separated from Hazelcast IMDG Reference Manual. Please see [here](http://docs.hazelcast.org/docs/management-center/3.8.3/manual/html/index.html).
|[Validating Secrets Using Strength Policy](/2000_Security/650_Validating_Secrets_Using_Strength_Policy.md)| Added as a new section.
|[Promoting Lite Members to Data Member](/17_Management/03_Cluster_Utilities/04_Enabling_Lite_Members.md)|Added as a new section.
|[Using the Script cluster.sh](/17_Management/03_Cluster_Utilities/02_Using_the_Script_cluster.sh.md)|Added the explanation for the new cluster state `NO_MIGRATION`.
|[Using REST API for Cluster Management](/1900_Management/400_Cluster_Utilities/400_Using_REST_API_for_Cluster_Management.md)| Added information on the `curl` commands for cluster version management.| 
|[Defining Member Attributes](/17_Management/03_Cluster_Utilities/05_Defining_Member_Attributes.md)|Added information related to member filtering for distributed class loading (user code deployment)
|[Diagnostics](/1900_Management/500_Diagnostics.md)| Added explanations for two new diagnostic plugins: OperationsHeartbeat and MemberHeartbeat.
|[Health Check and Monitoring](/1900_Management/400_Cluster_Utilities/800_Health_Check_and_Monitoring.md)|Added as a new section.
|[Native Client Security](/18_Security/08_Native_Client_Security.md)|Added description for the Cache Permissions.|
|[Near Cache](/19_Performance/04_Near_Cache/06_Near_Cache_Consistency.md)|Added "Locally Initiated Changes" as a new section.<br> Added the description for the newly introduced `serialize-keys` configuration element.
|[PartitioningStrategy](/2100_Performance/100_Data_Affinity.md)|Added as a new section to explain how Hazelcast provides data affinity using several partitioning strategies.|
|[Defining WAN replication using Discovery SPI](/2300_WAN_Replication/100_Defining_WAN_Replication.md)| Added the new section to explain how to use WAN with endpoints on various cloud infrastructures (such as Amazon EC2) where the IP addresses are not known in advance.
|[WAN Replication Failure Detection and Recovery](/2300_WAN_Replication/1150_WAN_Replication_Failure_Detection_and_Recovery.md)| Added as a new section.
|[System Properties](/2700_System_Properties)|Added definitions for the following new properties: <br> - hazelcast.partition.migration.fragments.enabled <br> - hazelcast.diagnostics.max.rolled.file.size.mb <br> - hazelcast.diagnostics.max.rolled.file.count<br> - hazelcast.diagnostics.operation-heartbeat.seconds <br> - hazelcast.diagnostics.operation-heartbeat.max-deviation-percentage <br> - hazelcast.diagnostics.member-heartbeat.seconds <br> - hazelcast.diagnostics.member-heartbeat.max-deviation-percentage <br> - hazelcast.legacy.memberlist.format.enabled <br> - hazelcast.mastership.claim.timeout.seconds <br> - hazelcast.heartbeat.failuredetector.type <br> - hazelcast.heartbeat.phiaccrual.failuredetector.threshold <br> - hazelcast.heartbeat.phiaccrual.failuredetector.sample.size <br> - hazelcast.heartbeat.phiaccrual.failuredetector.min.std.dev.millis <br> - hazelcast.operation.fail.on.indeterminate.state <br> - hazelcast.wan.map.useDeleteWhenProcessingRemoveEvents
|[System Properties - Client](/2700_System_Properties/200_System_Properties_-_Client.md)|Added client statistics related system properties definitions.
