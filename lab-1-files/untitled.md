# Create FTP to FTP Integration

* Click on the **`Integrations`** tab.
* Click on the **`Create Integration`** button.

![](../.gitbook/assets/image%20%28155%29.png)

* Select **Openshift FTP** as the starting connection for the integration.

![](../.gitbook/assets/image%20%2823%29.png)

* Select the only available action: **Download**.

![](../.gitbook/assets/image%20%2898%29.png)

* Enter the following values:

| File name expression | file1.xml |
| --- | --- | --- |
| FTP directory | incoming |
| Delete file after download | Yes |

* Click on the **`Next`** button.

![](../.gitbook/assets/image%20%2831%29.png)

* Click on the **`Done`** button.

![](../.gitbook/assets/image%20%28143%29.png)

* Select **Openshift FTP** as the finish connection.

![](../.gitbook/assets/image%20%28147%29.png)

* Select the only available action: **Upload**.

![](../.gitbook/assets/image%20%28119%29.png)

* Enter the following values:

| File name expression | ${date:now:yyyyMMdd}.xml |
| --- | --- |
| FTP directory | outgoing |

* Click on the **`Next`** button.

![](../.gitbook/assets/image%20%28118%29.png)

* Click on the **`Done`** button.
* Click on the **`Publish`** button.

![](../.gitbook/assets/image%20%2857%29.png)

* Enter **`FTP to FTP`** as the integration name.
* Click on the **`Publish`** button.

![](../.gitbook/assets/image%20%28114%29.png)

{% hint style="info" %}
After ~5min the deployment of the integration should be done.
{% endhint %}

![](../.gitbook/assets/image%20%2888%29.png)

