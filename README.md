# ords


```
[oracle@orcl11g ~]$ cd /u01/ords/
[oracle@orcl11g ords]$ cp /tmp/ords-20.3.0.301.1819.zip .
[oracle@orcl11g ords]$ unzip ords-20.3.0.301.1819.zip
Archive:  ords-20.3.0.301.1819.zip
   creating: installer/
   creating: params/
   creating: examples/
   creating: examples/soda/
   creating: examples/soda/getting-started/
   creating: examples/db_auth/
   creating: examples/db_auth/sql/
   creating: examples/application-container/
   creating: examples/pre_hook/
   creating: examples/pre_hook/sql/
   creating: examples/plugins/
   creating: examples/plugins/plugin-echo-cmd/
   creating: examples/plugins/plugin-echo-cmd/src/
   creating: examples/plugins/plugin-demo/
   creating: examples/plugins/plugin-demo/src/
   creating: examples/plugins/lib/
   creating: docs/
   creating: docs/javadoc/
   creating: docs/javadoc/plugin-api/
   creating: docs/javadoc/plugin-api/META-INF/
   creating: docs/javadoc/plugin-api/doc-files/
   creating: docs/javadoc/plugin-api/oracle/
   creating: docs/javadoc/plugin-api/oracle/dbtools/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/
   creating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/
  inflating: docs/javadoc/plugin-api/META-INF/MANIFEST.MF
  inflating: docs/javadoc/plugin-api/doc-files/route-patterns.html
  inflating: docs/javadoc/plugin-api/help-doc.html
  inflating: docs/javadoc/plugin-api/index.html
  inflating: docs/javadoc/plugin-api/overview-frame.html
  inflating: docs/javadoc/plugin-api/package-list
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/IOStreams.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/io/class-use/IOStreams.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/MultiMap.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/collections/class-use/MultiMap.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/Argument.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/Command.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/Option.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/class-use/Argument.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/class-use/Command.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/annotations/class-use/Option.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONArray.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/JSONToken.Type.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/JSONToken.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/JSONStreams.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/JSONIOException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/JSONToken.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/JSONReader.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/JSONWriter.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/JSONStreams.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/AuthenticationChallenge.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/Privilege.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/TransportPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/class-use/Privilege.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/class-use/Transport.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/HasPrivileges.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/AuthorizationConstraint.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/PathTemplate.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/DisabledBy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/Dispatches.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/RequiresPrivilege.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/PageSize.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/ConfigurationSetting.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/TimeDuration.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/class-use/ConfigurationSetting.Description.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/class-use/ConfigurationSetting.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeQualifier.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeInstantiator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeDependencyNotAvailableException.html 
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeQualifier.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeDependency.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/RequestScoped.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/Provides.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/class-use/Priority.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/class-use/Provides.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/class-use/ApplicationScoped.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/PriorityComparator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/AnnotationsProvider.html
  inflating: docs/javadoc/plugin-api/doc-files/developer-guide.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/CommandProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/cmdline/class-use/CommandProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONObject.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONNode.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONObject.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONNode.Type.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONNode.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/IntroducedSince.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/Accepts.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/class-use/Log.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeDependencyNotAvailableException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeQualifier.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeDependency.Kind.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/Primitive.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/JDBCDataSources.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/package-use.html
  inflating: docs/javadoc/plugin-api/doc-files/getting-started.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONArray.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONArray.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/JSONObjects.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONObject.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/Privileges.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/HasPrivileges.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/PrivilegeSet.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/AuthorizationConstraint.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/PrivilegeSets.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/AuthorizationError.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/PrivilegeSet.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/AuthenticationChallenge.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/PrivilegeConstraints.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/PrivilegeConstraints.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/Documentation.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/CrossOriginSharingPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/DocumentationPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/ExtensionPoints.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/ResolvedInstances.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/Optional.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/ApplicationScoped.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/class-use/Optional.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/class-use/RequestScoped.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/InstanceProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/Annotations.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/Instances.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/DeferredInstanceProviderCycleException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/InstanceLocator.html
  inflating: docs/javadoc/plugin-api/script.js
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONNode.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONObject.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONNode.Type.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONNode.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONArray.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/objects/class-use/JSONObjects.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/JSONIOException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/JSONReader.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/JSONWriter.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/json/class-use/JSONToken.Type.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/DocumentationPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/DisabledBy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/Dispatches.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/PathSyntaxPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/EnabledBy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/HTTPAuthenticationScheme.html 
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/RemovedSince.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/FramePolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/DeprecatedSince.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/EnabledBy.Condition.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/BelongsTo.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/FrameOptions.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/CORS.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/logging/Log.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/ConfigurationSetting.Description.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/ConfigurationSetting.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/Instantiator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/AvailableDependencies.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/Annotations.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/Instances.QualifiedInstance.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/ResolvedInstances.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/Instances.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/InstanceProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/PriorityComparator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/AnnotationsProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/Annotations.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/Instances.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/DeferredInstanceProviderCycleException.html 
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/InstanceLocator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/Instantiator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/AvailableDependencies.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/Annotations.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/class-use/DeferredInstanceProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/DeferredInstanceProvider.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/TranslatableText.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/class-use/TranslatableText.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/class-use/TranslatableDescription.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/annotations/TranslatableDescription.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/LocalePreference.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/class-use/LocalePreference.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/class-use/Translatable.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/i18n/Translatable.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/class-use/ExtensionPoints.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/class-use/Lifecycle.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/PathTemplateMatch.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/class-use/PathTemplateMatch.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/class-use/PathTemplates.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/routes/PathTemplates.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/ForwardedRequests.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/HasDynamicAuthorization.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/VersionedPlugins.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/FilterOrder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/HasGetMethod.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/EntityTag.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/VersionedPlugin.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/HttpServletBase.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/SupportsPatch.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/EntityTags.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/ErrorResponseHandler.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/ForwardedRequests.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/HasDynamicAuthorization.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/VersionedPlugins.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/FilterOrder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/HasGetMethod.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/EntityTag.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/VersionedPlugin.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/HttpServletBase.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/SupportsPatch.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/EntityTags.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/ErrorResponseHandler.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/EntityTag.Strength.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/class-use/EntityTag.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/EntityTag.Strength.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/servlet/EntityTag.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/Lifecycle.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/PaginationMetadata.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/PaginationStrategy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/Pagination.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/PaginationContext.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/PaginationContext.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/Pagination.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/PaginationContext.Builder.html
  inflating: docs/javadoc/plugin-api/allclasses-frame.html
  inflating: docs/javadoc/plugin-api/deprecated-list.html
  inflating: docs/javadoc/plugin-api/allclasses-noframe.html
  inflating: docs/javadoc/plugin-api/serialized-form.html
  inflating: docs/javadoc/plugin-api/index-all.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/Configuration.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/class-use/ConfigurationSetting.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/class-use/Configuration.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/conf/class-use/TimeDuration.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/AnnotationSet.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/PrimitiveWrapper.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeReflection.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeInstantiator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/package-frame.html
  inflating: docs/javadoc/plugin-api/constant-values.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/Transport.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/NotAuthorizedException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/EndUserAuthorizationConstraint.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/Privileges.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/PrivilegeSet.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/PrivilegeSets.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/AuthorizationError.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/AuthenticationChallenge.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeDependency.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/ProvidedClassifier.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeLocator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeDependencies.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeDependency.Kind.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/ProvidedClassifier.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/Primitive.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeLocator.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeDependencies.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeQualifier.MatchingMode.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeReflections.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeReflections.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeReflections.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/SchemaNotAvailableException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/class-use/SchemaNotAvailableException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/JDBCDataSource.html
  inflating: docs/javadoc/plugin-api/overview-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/PathSyntaxPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/HTTPAuthenticationScheme.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/FramePolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/DeprecatedSince.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/RequiresPrivilege.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/EnabledBy.Condition.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/PageSize.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/BelongsTo.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/FrameOptions.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/IntroducedSince.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/CORS.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/Accepts.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/Documentation.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/CrossOriginSharingPolicy.html 
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/class-use/PathTemplate.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/PaginationState.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/PaginationMetadata.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/PaginationStrategy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/PaginationState.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/pagination/class-use/PaginationContext.html
  inflating: docs/javadoc/plugin-api/overview-tree.html
  inflating: docs/javadoc/plugin-api/stylesheet.css
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/annotations/class-use/TransportPolicy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/PrivilegeSet.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/AuthenticationChallenge.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/NotAuthorizedException.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/security/class-use/EndUserAuthorizationConstraint.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/EnabledBy.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/RemovedSince.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/package-summary.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/http/annotations/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeQualifier.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeQualifier.MatchingMode.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/TypeReflections.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/AnnotationSet.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/PrimitiveWrapper.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/types/class-use/TypeReflection.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/class-use/JDBCDataSources.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/jdbc/class-use/JDBCDataSource.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/package-frame.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/package-use.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/package-tree.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/Instances.QualifiedInstance.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/Instances.Builder.html
  inflating: docs/javadoc/plugin-api/oracle/dbtools/plugin/api/di/annotations/Priority.html
  inflating: index.html
  inflating: examples/soda/getting-started/indexSpec1.json
  inflating: examples/application-container/README.md
  inflating: examples/plugins/plugin-demo/src/PluginDemo.java
  inflating: examples/plugins/plugin-demo/build.xml
  inflating: ords.war
  inflating: installer/ords_installer_privileges.sql
  inflating: examples/soda/getting-started/qbePatch.json
  inflating: examples/db_auth/sql/uninstall.sql
  inflating: examples/plugins/plugin-echo-cmd/src/EchoMessages.properties
  inflating: examples/plugins/plugin-echo-cmd/src/EchoMessages.java
  inflating: examples/plugins/plugin-echo-cmd/src/EchoCommand.java
  inflating: examples/plugins/plugin-echo-cmd/build.xml
  inflating: params/ords_params.properties
  inflating: examples/db_auth/sql/install.sql
  inflating: examples/pre_hook/sql/uninstall.sql
  inflating: examples/soda/getting-started/QBE.2.json
  inflating: examples/db_auth/index.html
  inflating: examples/pre_hook/sql/custom_auth_api.plb
  inflating: examples/soda/getting-started/poUpdated.json
  inflating: examples/soda/getting-started/poPatchSpec.json
  inflating: examples/pre_hook/sql/custom_auth_api.pls
  inflating: examples/soda/getting-started/QBE.3.json
  inflating: examples/soda/getting-started/QBE.5.json
  inflating: examples/pre_hook/sql/install.sql
  inflating: 
  
  examples/soda/getting-started/QBE.1.json
  inflating: examples/soda/getting-started/POList.json
  inflating: examples/pre_hook/index.html
  inflating: examples/soda/getting-started/QBE.4.json
  inflating: examples/soda/getting-started/po.json
  inflating: examples/pre_hook/README.md
  inflating: examples/plugins/lib/javax.inject-1.jar
[oracle@orcl11g ords]$ ls
docs  examples  index.html  installer  ords-20.3.0.301.1819.zip  ords.war  params
[oracle@orcl11g ords]$ java -jar ords.war
This Oracle REST Data Services instance has not yet been configured.
Please complete the following prompts


Enter the location to store configuration data: /u01/ords
Enter the name of the database server [localhost]:^C
[oracle@orcl11g ords]$
[oracle@orcl11g ords]$
[oracle@orcl11g ords]$
[oracle@orcl11g ords]$ ps -ef | grep pmon
grid     54563     1  0 05:44 ?        00:00:01 asm_pmon_+ASM1
oracle   59337 56667  0 12:17 pts/0    00:00:00 grep --color=auto pmon
grid     63736     1  0 05:46 ?        00:00:01 apx_pmon_+APX1
oracle   90461     1  0 05:58 ?        00:00:03 ora_pmon_orcl11g
[oracle@orcl11g ords]$ java -jar ords.war
Enter the name of the database server [localhost]:orcl11g
Enter the database listen port [1521]:
Enter 1 to specify the database service name, or 2 to specify the database SID [1]:2
Enter the database SID [xe]:orcl11g
Enter the database password for ORDS_PUBLIC_USER:
Confirm password:
Requires to login with administrator privileges to verify Oracle REST Data Services schema.

Enter the administrator username:sys as sysdba
Enter the database password for sys as sysdba:
Confirm password:
Connecting to database user: sys as sysdba url: jdbc:oracle:thin:@orcl11g:1521:orcl11g

Retrieving information.
Enter 1 if you want to use PL/SQL Gateway or 2 to skip this step.
If using Oracle Application Express or migrating from mod_plsql then you must enter 1 [1]:1
Enter the database password for APEX_PUBLIC_USER:
Confirm password:
Enter 1 to specify passwords for Application Express RESTful Services database users (APEX_LISTENER, APEX_REST_PUBLIC_USER) or 2 to skip this step [1]:1
Enter the database password for APEX_LISTENER:
Confirm password:
Enter the database password for APEX_REST_PUBLIC_USER:
Confirm password:
Enter a number to select a feature to enable:
   [1] SQL Developer Web  (Enables all features)
   [2] REST Enabled SQL
   [3] Database API
   [4] REST Enabled SQL and Database API
   [5] None
Choose [1]:1
2020-12-29T12:21:15.859Z INFO        reloaded pools: []
Installing Oracle REST Data Services version 20.3.0.r3011819
... Log file written to /home/oracle/ords_install_core_2020-12-29_122116_00039.log
... Verified database prerequisites
... Created Oracle REST Data Services proxy user
... Created Oracle REST Data Services schema
... Granted privileges to Oracle REST Data Services
... Created Oracle REST Data Services database objects
... Log file written to /home/oracle/ords_install_datamodel_2020-12-29_122131_00424.log
... Log file written to /home/oracle/ords_install_apex_2020-12-29_122132_00550.log
Completed installation for Oracle REST Data Services version 20.3.0.r3011819. Elapsed time: 00:00:17.636

Enter 1 if you wish to start in standalone mode or 2 to exit [1]:1
Enter the APEX static resources location:/u01/ords
Enter 1 if using HTTP or 2 if using HTTPS [1]:1
2020-12-29T12:21:59.270Z INFO        HTTP and HTTP/2 cleartext listening on host: localhost port: 8080
2020-12-29T12:21:59.364Z INFO        Disabling document root because the specified folder does not exist: /u01/ords/ords/standalone/doc_root
2020-12-29T12:22:02.345Z WARNING     The pool named: |apex|| is invalid and will be ignored: The username or password for the connection pool named |apex||, are invalid, expired, or the account is locked
2020-12-29T12:22:02.733Z INFO        Configuration properties for: |apex|pu|
cache.caching=false
cache.directory=/tmp/apex/cache
cache.duration=days
cache.expiration=7
cache.maxEntries=500
cache.monitorInterval=60
cache.procedureNameList=
cache.type=lru
database.api.enabled=true
db.connectionType=basic
db.hostname=orcl11g
db.port=1521
db.sid=orcl11g
debug.debugger=false
debug.printDebugToScreen=false
error.keepErrorMessages=true
error.maxEntries=50
feature.sdw=true
jdbc.DriverType=thin
jdbc.InactivityTimeout=1800
jdbc.InitialLimit=3
jdbc.MaxConnectionReuseCount=1000
jdbc.MaxLimit=10
jdbc.MaxStatementsLimit=10
jdbc.MinLimit=1
jdbc.statementTimeout=900
log.logging=false
log.maxEntries=50
misc.compress=
misc.defaultPage=apex
restEnabledSql.active=true
security.disableDefaultExclusionList=false
security.maxEntries=2000
security.requestValidationFunction=wwv_flow_epg_include_modules.authorize
security.validationFunctionType=plsql
db.password=******
db.username=ORDS_PUBLIC_USER
resource.templates.enabled=true

2020-12-29T12:22:02.740Z WARNING     *** jdbc.MaxLimit in configuration |apex|pu| is using a value of 10, this setting may not be sized adequately for a production environment ***
2020-12-29T12:22:02.741Z WARNING     *** jdbc.InitialLimit in configuration |apex|pu| is using a value of 3, this setting may not be sized adequately for a production environment ***
2020-12-29T12:22:04.321Z WARNING     The pool named: |apex|rt| is invalid and will be ignored: The username or password for the connection pool named |apex|rt|, are invalid, expired, or the account is locked
2020-12-29T12:22:04.453Z WARNING     The pool named: |apex|al| is invalid and will be ignored: The username or password for the connection pool named |apex|al|, are invalid, expired, or the account is locked
2020-12-29T12:22:10.927Z INFO        Oracle REST Data Services initialized
Oracle REST Data Services version : 20.3.0.r3011819
Oracle REST Data Services server info: jetty/9.4.30.v20200611



```
