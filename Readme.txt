# 32 ビット版の SSIS で実行することを想定

C:\Program Files (x86)\Microsoft SQL Server\130\DTS\Binn に Newtonsoft.Json.dll を配置
Run64BitRuntime を False に設定
"C:\Program Files (x86)\Microsoft SQL Server\130\DTS\Binn\dtexec.exe" /File ".\JSONCustomScript.dtsx" /SET \Package.Variables[$Package::ImportPath];"C:\ImportData"

/*
Drop Table if exists tempdb..TableDefinition1
Drop Table if exists tempdb..TableDefinition2
select * from tempdb..TableDefinition1
select * from tempdb..TableDefinition2
*/