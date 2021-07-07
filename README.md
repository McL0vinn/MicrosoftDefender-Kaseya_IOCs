# Kaseya_IOC
Simple KQL query that can be run either in MD for Endpoint (Threat hunting or custom indicator) or in Azure Sentinel (Threat hunting or analytics rule)
It's looking for 4 known IOCs related to the Kaseya attack
Its the SHA256 hashes of the below files

agent.crt - 2093c195b6c1fd6ab9e1110c13096c5fe130b75a84a27748007ae52d9e951643
agent.exe - d55f983c994caa160ec63a59f6b4250fe67fb3e8c43a388aec60a4a6978e9f1e
mpsvc.dll - e2a24ab94f865caeacdf2c3ad015f31f23008ac6db8312c2cbfb32e4a5466ea2
mpsvc.dll - 8dd620d9aeb35960bb766458c8890ede987c33d239cf730f93fe49d90ae759dd

https://www.bleepingcomputer.com/news/security/kaseya-roughly-1-500-businesses-hit-by-revil-ransomware-attack/
