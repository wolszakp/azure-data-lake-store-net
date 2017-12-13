# Changes to the SDK
### Version 1.0.3
- Fix account validation
### Version 1.0.2
- Fix path encoding
- Changed Api version
- Strongly name and sign the assemblies
- Fix the implict reference problem
- Remove the reference to NLog.config
- Make the async methods virtual and make some contructors public or protected to make unit testing with Moq like tools easier.
### Version 1.0.1
- Added feature resume in upload and download, non-binary uploads, recursive acl processor, diskusage, acl dump. Added Mock client for unit test. Fixed doc generation.
### Version 1.0.0
- Add bulk upload and bulk download
### Version 0.1.3-beta
- Fix the Newtonsoft.Json reference to 6.0.8 for .NET452 to be compatible with powershell and other azure libraries
### Version 0.1.2-beta
- Fix objectid bug in Core.getfileliststatus and Core.getaclstatus and add unit test for it
- Remove blocksize and replicationfactor from directory entry
- Change parameter names for some public APIs
### Version 0.1.1-beta
- Reference Microsoft.Rest.ClientRuntime instead of Microsoft.Rest.ClientRuntime.Azure.Authentication in Microsoft.Azure.DataLake.Store project.
- Reference Microsoft.Rest.ClientRuntime.Azure.Authentication in Microsoft.Azure.DataLake.Store.UnitTest.
### Version 0.1.0-beta
- Initial PreRelease