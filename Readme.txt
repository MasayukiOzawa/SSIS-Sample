# 32 �r�b�g�ł� SSIS �Ŏ��s���邱�Ƃ�z��

C:\Program Files (x86)\Microsoft SQL Server\130\DTS\Binn �� Newtonsoft.Json.dll ��z�u
Run64BitRuntime �� False �ɐݒ�
"C:\Program Files (x86)\Microsoft SQL Server\130\DTS\Binn\dtexec.exe" /File ".\JSONCustomScript.dtsx" /SET \Package.Variables[$Package::ImportPath];"C:\ImportData"

/*
Drop Table if exists tempdb..TableDefinition1
Drop Table if exists tempdb..TableDefinition2
select * from tempdb..TableDefinition1
select * from tempdb..TableDefinition2
*/