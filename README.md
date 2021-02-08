# Sample Configuration Files for Windows Sandbox for Windows 10

[Microsfot Docs](https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-overview)

#### **`Default.wsb`**

``` xml
<Configuration>
  <VGpu>Default</VGpu>
  <Networking>Default</Networking>
  <MappedFolders>
    <MappedFolder>
      <HostFolder>C:\Users\Public\Downloads</HostFolder>
      <SandboxFolder>C:\Users\WDAGUtilityAccount\Downloads</SandboxFolder>
      <ReadOnly>true</ReadOnly>
    </MappedFolder>
  </MappedFolders>
  <LogonCommand>
    <Command>explorer.exe C:\users\WDAGUtilityAccount\Downloads</Command>
  </LogonCommand>
  <AudioInput>Default</AudioInput>
  <VideoInput>Default</VideoInput>
  <ProtectedClient>Default</ProtectedClient>
  <PrinterRedirection>Default</PrinterRedirection>
  <ClipboardRedirection>Default</ClipboardRedirection>
  <MemoryInMB>4096</MemoryInMB>
</Configuration>
```
