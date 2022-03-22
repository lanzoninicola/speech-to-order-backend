<h1 align="center" style="border-bottom: none;">🎤 Speech to Text Demo </h1>
<h3 align="center">Backend layer of application using IBM Watson Speech to Text service features.</h3>

## Deploying to IBM Cloud as a Cloud Foundry Application

1. Login to IBM Cloud with the [IBM Cloud CLI](https://cloud.ibm.com/docs/cli?topic=cloud-cli-getting-started#overview)

    ```
    ibmcloud login
    ```

2. Target a Cloud Foundry organization and space.

    ```
    ibmcloud target --cf
    ```

3. Edit the *manifest.yml* file. Change the **name** field to something unique. For example, `- name: my-app-name`.
4. Deploy the application

    ```
    ibmcloud app push
    ```


## API URL

https://speech-to-order-backend.eu-gb.mybluemix.net/api/speech-to-text/token