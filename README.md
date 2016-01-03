# Oracle BPM Instance Migration
Oracle BPM in-flight instance migration on Humantask and other components.

Instance Migration allows you to migrate selected composite instances between existing compatible composite revisions or from an existing revision to a new revision.

 1. **Alterflow XSD Schema**
This schema file define the migration tasks [alterflow, flowUpdate, data Update etc...].

 2. **Project_Sample_Source_files**
 The Sample BPM Projects [aaMig11_1.0, aaMig11_2.0] with Humantask 'UserTask' and 'UserTask1'.
 
 3. **Project_Sample_AntTask_files_and_results**
 	 5. build.xml - The ant task script file.
 	 6. migration_report.xml - Based on migration report, write the migration plan.
	 2. migration_plan.xml - Plan to migrate components from version to version.
	 3. migration_result.xml - The execution result of migration plan. 
	 Show the number of success, failure migrated instance details and if any error message.
	 4. After_migration_Flow_trace.jpeg - Flow trace show the migrated instance gone to stale state.
	 5. After_migration_Aduit_trail_Payload.jpeg - Audit trail show the Instance Moved to new/target activity.

The complete article can be found in my blog [http://technology-oraclefmw.com](http://technology-oraclefmw.com/oracle-bpm-instance-migration/).




