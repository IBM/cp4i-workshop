# Pre-work

## Deploy Traderlite operator

1. To deploy Traderlite operator, you will need OpenShift cluster name and APIKey of your IBM cloud account. Refer to [Creating an IBM Cloud API key](https://www.ibm.com/docs/en/app-connect/containers_cd?topic=servers-creating-cloud-api-key) if you don't have an APIKey already.

2. Clone [repo](https://github.com/IBM/cp4i-workshop)

   2.1 On your terminal window, in your preferred directory, run the below command to clone the repo
    ```
    git clone https://github.com/IBM/cp4i-workshop.git
    ```

   2.2 In cloned repo, change directory to folder where Tradelite operator install script is available.
    ```
    cd cp4i-workshop/pre-work/
    ```
   2.3 Install Traderlite Operator using the command
   ```
   ./install-trader-operator.sh CLUSTER_NAME API_KEY
   ```
