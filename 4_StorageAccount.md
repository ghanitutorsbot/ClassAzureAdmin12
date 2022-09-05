

Storage options

        Storage accounts
                Blob Service
                File Service
                Table
                Queue


Creation of Storage Account

    Storage account name - mandatory (unique/universal)
    Region - Eastus
    Performance - Standard/premium
    Redudancy - LRS (Locally Redudant Storage) - 3 copies
                - GRS (Geo Redudant Storage) - 6 copies [3 copies (same region) + 3 copies (Globally)] 
                - ZRS (Zone Redudant Storage) - 3 copies (az1 -1, az-2)
                - GZRS (Geo Zone redudant storage) - 6 copies [(3 copies ZRS) + 3 Copies (Globally)]

    
    Access Tier - Pricing - Access (transaction charges), storage (1gb)
                      Hot - Transaction Charges -Lower + Storage cost - Higher (Normal)
                      Cold - Transaction Charges - Higher + Storage cost - Lower (Backup)

