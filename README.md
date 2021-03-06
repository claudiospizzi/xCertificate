# xCertificate

The **xCertificate** module is a part of the Windows PowerShell Desired State
Configuration (DSC) Resource Kit, which is a collection of DSC Resources. This
module includes DSC resources that simplify administration of certificates on a
Windows Server, with simple declarative language.

The **xCertificate** module contains the following resources:

- **xCertificateExport**: Used to export a certificate from a Windows certificate
  store.
- **xCertificateImport**: Used to import a certificate into a Windows certificate
  store.
- **xCertReq**: Used to request a new certificate from an certificate authority.
- **xPfxImport**: Used to import a PFX certificate into a Windows certificate store.
- **xWaitForCertificateServices**: Used to wait for a Active Directory Certificate
  Services Certificate Authority to become available.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any
additional questions or comments.

## Documentation and Examples

For a full list of resources in xCertificate and examples on their use, check out
the [xCertificate wiki](https://github.com/PowerShell/xCertificate/wiki).

## Branches

### master

[![Build status](https://ci.appveyor.com/api/projects/status/0u9f8smiidg1j4kn/branch/master?svg=true)](https://ci.appveyor.com/project/PowerShell/xCertificate/branch/master)
[![codecov](https://codecov.io/gh/PowerShell/xCertificate/branch/master/graph/badge.svg)](https://codecov.io/gh/PowerShell/xCertificate/branch/master)

This is the branch containing the latest release - no contributions should be made
directly to this branch.

### dev

[![Build status](https://ci.appveyor.com/api/projects/status/0u9f8smiidg1j4kn/branch/dev?svg=true)](https://ci.appveyor.com/project/PowerShell/xCertificate/branch/dev)[![codecov](https://codecov.io/gh/PowerShell/xCertificate/branch/dev/graph/badge.svg)](https://codecov.io/gh/PowerShell/xCertificate/branch/dev)

This is the development branch to which contributions should be proposed by contributors
as pull requests. This development branch will periodically be merged to the master
branch, and be released to [PowerShell Gallery](https://www.powershellgallery.com/).

## Contributing

Please check out common DSC Resources [contributing guidelines](https://github.com/PowerShell/DscResource.Kit/blob/master/CONTRIBUTING.md).
