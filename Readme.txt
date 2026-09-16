New-Item -Path HKLM:\SOFTWARE\Policies\Google\Chrome -Name ExtensionInstallSources -Force
New-ItemProperty -Path HKLM:\SOFTWARE\Policies\Google\Chrome\ExtensionInstallSources -Name "1" -Value "https://hidigitalworkplace.github.io/*" -Force
New-Item -Path HKLM:\SOFTWARE\Policies\Google\Chrome -Name ExtensionInstallAllowlist -Force
New-ItemProperty -Path HKLM:\SOFTWARE\Policies\Google\Chrome\ExtensionInstallAllowlist -Name "1" -Value "djepcndaenfdpllpcocpcpnfookjdcac" -Force
New-Item -Path HKLM:\SOFTWARE\Policies\Google\Chrome -Name ExtensionInstallForcelist -Force
New-ItemProperty -Path HKLM:\SOFTWARE\Policies\Google\Chrome\ExtensionInstallForcelist -Name "1" -Value "djepcndaenfdpllpcocpcpnfookjdcac;https://hidigitalworkplace.github.io/Extensions/manifest.xml" -Force
