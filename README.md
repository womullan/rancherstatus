# Example rancher API to get Yagen node status. 

First install teh client api 
 pip install git+https://github.com/rancher/client-python.git@master

get credentials from Rancher click on avatar select API Keys Create a new API key put bearer_token in secrets.json


## secrets.son file should look like

    { 
        "access_key": "token-fq..", 
        "secret_key": "ihg9x...", 
        "bearer_token": "token-fq....ih...." i
    }



