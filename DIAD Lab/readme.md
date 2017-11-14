## Notice
To deploy this solution you need to have access to the scripts stored in Key Vault. Unless you have access to the Key Vault you will not be able to deploy it. Thank you.

## Details
This solution deploys two ADDS DCs (CONTOSO.COM), one optional VM into this domain and one Jump Server to connect into this environment from the Internet. 

Jump Server VM will have Public IP assigned to it. You will need to change NSG rule to allow access to the Public IP. Either do this during initial deployment or later on in NSG. 
Provide your PC Internet IP or * if ok with everyone else on the Internet trying to get access to it - see Notice/Warning below.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdmitriilezine%2FDIAD-Lab%2Fmaster%2FDIAD%20Lab%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


## Notice/Warning
* This template is designed for a lab environment and demonstration purposes.