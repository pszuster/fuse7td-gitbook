# Check that DB table is empty

* Go to [http://db.ignite1.rhtechofficelatam.com](http://db.ignite1.rhtechofficelatam.com)
* Login as:
  * **User**: admin@ignite.com
  * **Password**: password
* Click on  **Add New Server.**

![](../../.gitbook/assets/image%20%2868%29.png)

* Enter **igniteDB** as **Name.**

![](../../.gitbook/assets/image%20%2879%29.png)

* Click on the **Connection** tab.
* Enter the following values:

| **Host** | ignitedb.db.svc.cluster.local |
| --- | --- | --- | --- |
| **Port** | 5432 |
| **Username** | admin |
| **Password** | admin |

* Click on the **Save** button.

![](../../.gitbook/assets/image%20%2850%29.png)

* Expand **Servers -&gt; IgniteDB -&gt; Databases -&gt; JBossBank -&gt; Schemas -&gt; Public -&gt; Tables**
* Right-click on the **`contacts`** table, and select **`View/Edit Data -> All Rows`.**

![](../../.gitbook/assets/image%20%28150%29.png)

{% hint style="info" %}
Note that the table is empty.
{% endhint %}



