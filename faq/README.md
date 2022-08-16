# Frequently Asked Questions & Helpful Tips / Tricks

1. [I don't have the trader lite application, how can I install it?](#traderlite-application-installation)
1. [I am receiving a `Your connection is not private` message, what should I do?](#accept-private-connection)

>**Note:** You can click on any image in the instructions below to zoom in and see more details. When you do that just click on your browser's back button to return to the previous state.

***

## Traderlite Application Installation

The traderlite application used in this workshop is installed as part of the API Connect and/or the Salesforce integration labs. If you have not completed that lab, follow these steps to install an instance of the application.

1. In a separate browser tab, go to the OpenShift console of your assigned cluster.

1. Click on **Projects** in the left navigation and then click on your ***studentnnn*** project in the list.

    [![](../exercise-api-connect/images/select-traderlite-project.png)](../exercise-api-connect/images/select-traderlite-project.png)

1. Click on **Installed Operators** in the left navigation and then click on the **TraderLite Operator** in the list.

    [![](../exercise-api-connect/images/select-traderlite-operator.png)](../exercise-api-connect/images/select-traderlite-operator.png)

1. Click the **Create Instance** to start the installation of the TraderLite app.

    [![](../exercise-api-connect/images/traderlite-create-instance.png)](../exercise-api-connect/images/traderlite-create-instance.png)

1. Name the instance *traderlite* and leave everything else with their default values. Click **Create**

    [![](images/traderlite-create-values-default.png)](images/traderlite-create-values-default.png)

1. In the left navigation select **Pods** in the **Workloads** section and then wait for all the TraderLite pods to have a status of **Running** and be in the **Ready** state.

    > *Note: You can enter `traderlite` in the search by name input field to filter the pods.*

    [![](../exercise-api-connect/images/traderlite-pods-ready.png)](../exercise-api-connect/images/traderlite-pods-ready.png)

## Accept Private Connection

There are various components used in this workshop. When loading the UIs for these components you may receive a message in your browser that the connection is not private. To complete loading the UI:

* Click the `Advanced` button below the warning message and then click the `Proceed to ....` link.

    [![](images/private-connection-message.png)](images/private-connection-message.png)

* You may receive this message more than once, follow the same steps to proceed to the UI.
