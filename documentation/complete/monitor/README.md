# Monitoring and Troubleshooting

1. Monitor IDOC in SAP ECC

You can check the status of outbound IDoc and act accordingly. If the IDoc is failed, then we have to to revisit the backend configuration and review all our steps.

1. Get the IDoc number after executing report.

    ![monitor](./images/ecc-mon-rep.png)

2. Enter Transaction **BD87**.

3. In the **IDoc Number** field, enter the number which you have fetched after running report. Execute the transaction.

    ![monitor](./images/ecc-mon-bd87.png)

4. If the IDoc is success, you will get a log **Data passed to port OK** with green icon. If the icon is in red, it means there is a failure in IDoc and then you have to revisit the backend setup.

    ![monitor](./images/ecc-mon-log.png)

