**Lab 3 -- Configuring Dual Write Table Maps**

## **Lab 3: Configuring Dual Write Table Maps**

In this exercise, you will complete the following procedures to
configure Dual-write and run Dual-write table maps.

### Task 1: Configure / Run Dual-write Table Maps

1.  Navigate back to **Finance and Operations** tab or go to
    <https://admin.powerplatform.microsoft.com/> and sign in with your
    Office 365 tenant credentials.

2.  Click on **Environment** and then click on your **Project Operations
    environment**.

    ![](./media/image48.png){width="6.5in"
    height="3.9833333333333334in"}![](./media/image2.png){width="6.5in"
    height="2.3833333333333333in"}

3.  Click on **Finance and Operations URL**

4.  Select **Dual-write**.

    ![](./media/image3.png){width="6.498611111111111in"
    height="2.0930555555555554in"}

### Task 2: Configure / Run Project resource roles for all companies (bookableresourcecategories)

1.  In the **Search** box (top right corner), type **Project Resource**
    to narrow down the results. Then select **Project resource roles for
    all companies (bookableresourcecategories)** and then click **Run**.

![Graphical user interface, text, application Description automatically
generated](./media/image4.png){width="6.5in"
height="1.5347222222222223in"}

5.  On the **Initial writes and related table map(s)** pane, select
    **Initial sync** check box, ensure that **Microsoft Dataverse** is
    selected and then click **Run**.

![Graphical user interface, application Description automatically
generated](./media/image5.png){width="6.5in" height="1.825in"}

![Graphical user interface, text, email Description automatically
generated](./media/image6.png){width="6.5in"
height="2.0118055555555556in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![Graphical user interface, text, application Description automatically
generated](./media/image7.png){width="6.493055555555555in"
height="1.5555555555555556in"}

*This may take a few minutes to complete.*

### Task 3: Configure / Run Legal entities (cdm_companies)

1.  In the Search box (top right corner), type **Legal entities** to
    narrow down the results. Then select **Legal entities
    (cdm_companies)** and then click **Run**.

    ![](./media/image8.png){width="6.5in" height="1.6in"}

2.  On the **Initial writes and related table map(s)** pane, select
    **Initial sync** check box, ensure that **Finance and Operations
    apps** is selected and then click **Run**.

    ![](./media/image9.png){width="6.491666666666666in" height="1.75in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![Graphical user interface, text, application Description automatically
generated](./media/image10.png){width="6.491666666666666in"
height="2.283333333333333in"}

*This may take a few minutes to complete.*

### Task 4: Configure / Run Ledger (msdyn_ledgers) 

1.  In the Search box (top right corner), type **Ledger** to narrow down
    the results. Then select **Ledger (msdyn_ledgers)** and then click
    **Run**

    ![](./media/image11.png){width="6.5in" height="1.9in"}

2.  On the **Initial writes and related table map(s)** pane, select
    **Initial sync** check box, ensure that **Finance and Operations
    apps** is selected. Turn on the **Show related table map(s)** toggle
    key.

    ![](./media/image12.png){width="6.0in"
    height="1.7270833333333333in"}

3.  *The related tables are displayed.*On the **Initial writes and
    related table map(s)** pane, select Intial sync for all thetable
    which are in Not Running status and **Maste of Intial Sync** to
    **Finance and Operatoins apps** then click **Run**.

    ![](./media/image13.png){width="6.5in" height="4.341666666666667in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image14.png){width="6.499305555555556in"
height="2.154861111111111in"}

### Task 5: Configure / Run Project Operations integration actuals (msdyn_actuals) 

1.  In the search box (top right corner), type **Project Operations
    integration actuals** to narrow down the results. Then select
    **Project Operations integration actuals (msdyn_actuals)** and then
    click **Run**

    ![](./media/image15.png){width="6.4875in"
    height="1.5118055555555556in"}

2.  On the **Initial writes and related table map(s)** pane, turn on the
    **Show related table map(s)** toggle key and then click on **Run**

    ![](./media/image16.png){width="6.4944444444444445in"
    height="4.340972222222222in"}

    *This can take 10-15 minutes to complete*

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image17.png){width="6.490972222222222in"
height="1.5909722222222222in"}

### Task 6: Configure/Run Project contract lines (salesorderdetails)

1.  In the search box (top right corner), type **Project contract
    lines** to narrow down the results. Then select **Project contract
    lines (salesorderdetails)** and then click **Run**

    ![](./media/image18.png){width="6.5in" height="1.601388888888889in"}

2.  On the **Initial writes and related table map(s)** pane, just click
    on **Run**.

    ![](./media/image19.png){width="6.495833333333334in"
    height="2.171527777777778in"}

3.  Select **Yes** on **Confirmation** dialog box.

    ![](./media/image20.png){width="6.495138888888889in"
    height="3.7354166666666666in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image21.png){width="6.5in" height="1.5409722222222222in"}

### Task 7: Configure/Run Integration entity for project transaction relationships (msdyn_transactionconnections)

1.  In the search box (top right corner), type **Integration entity for
    project transaction relationships** to narrow down the results. Then
    select **Integration entity for project transaction relationships
    (msdyn_transactionconnections)** and then click **Run**

![](./media/image22.png){width="6.490972222222222in"
height="1.5333333333333334in"}

2.  On the **Initial writes and related table map(s)** pane, click on
    **Run**

    ![](./media/image23.png){width="6.49375in"
    height="1.988888888888889in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image24.png){width="6.5in" height="1.6729166666666666in"}

### Task 8: Configure/Run Project Operations integration contract line milestones (msdyn_contractlinesscheduleofvalues)

1.  In the search box (top right corner), type **Project Operations
    integration contract line milestones** to narrow down the results.
    Then select **Operations integration contract line milestones
    (msdyn_contractlinesscheduleofvalues)** and then click **Run**

![](./media/image25.png){width="6.490277777777778in"
height="1.7805555555555554in"}

2.  On the **Initial writes and related table map(s)** pane, click on
    **Run**

    ![](./media/image26.png){width="6.497916666666667in"
    height="2.2368055555555557in"}

3.  If prompted, select **Yes** on **Confirmation** dialog box .

    ![](./media/image27.png){width="4.916666666666667in"
    height="1.9493055555555556in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image28.png){width="6.490277777777778in"
height="2.102777777777778in"}

### Task 9: Configure/Run Project Operations integration entity for expense estimates (msdyn_estimateslines)

1.  In the Search box (top right corner), **Project Operations
    integration entity for expense estimates** to narrow down the
    results. Then select **Project Operations integration entity for
    expense estimates (msdyn_estimateslines)** and then click **Run**

![](./media/image29.png){width="6.498611111111111in"
height="1.7305555555555556in"}

2.  On the **Initial writes and related table map(s)** pane, click on
    **Run**

    ![](./media/image30.png){width="6.493055555555555in"
    height="1.7881944444444444in"}

3.  On the **Confirmation** dialog box, click **Yes**.

    ![](./media/image27.png){width="4.916666666666667in"
    height="1.9493055555555556in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image31.png){width="6.490277777777778in"
height="2.057638888888889in"}

### Task 10: Configure/Run Project Operations integration project expense categories export entity (msdyn_expensecategories)

1.  In the search box (top right corner), **Project Operations
    integration project expense categories export entity** to narrow
    down the results. Then select **Project Operations integration
    project expense categories export entity (msdyn_expensecategories)**
    and then click **Run**

![](./media/image32.png){width="6.497222222222222in"
height="1.7034722222222223in"}

2.  On the **Initial writes and related table map(s)** pane, click on
    **Run**

    ![](./media/image33.png){width="6.491666666666666in"
    height="1.945138888888889in"}

3.  If prompted, then on the **Confirmation** dialog box, click **Yes**.

    ![](./media/image27.png){width="4.916666666666667in"
    height="1.9493055555555556in"}

**IMPORTANT:**Make sure to wait until the status displays **Running**
before proceeding to the next table map.

![](./media/image34.png){width="6.495833333333334in"
height="1.726388888888889in"}

### Task 11: Configure/Run Project Operations integration project expenses export entity (msdyn_expenses)

1.  In the search box (top right corner), **Project Operations
    integration project expenses export entity** to narrow down the
    results. Then click on your **Project Operations integration project
    expenses export entity (msdyn_expenses).**

> ![](./media/image35.png){width="6.4875in"
> height="1.7743055555555556in"}

2.  Select the **Table mappings** tab and in the top ribbon, click
    **Refresh tables**.

    ![](./media/image36.png){width="6.4944444444444445in"
    height="4.530555555555556in"}

```{=html}
<!-- -->
```
4.  After the refresh is complete, click **Run**.

    ![](./media/image37.png){width="6.5in" height="4.904166666666667in"}

5.  On the **Initial writes and related table maps(s)** page, click
    **Run**.

    ![](./media/image38.png){width="6.492361111111111in"
    height="1.9381944444444446in"}

6.  On the **Confirmation** dialog box, click **Yes**.

    ![](./media/image27.png){width="4.916666666666667in"
    height="1.9493055555555556in"}

7.  Click on **Dual-Write**

    ![](./media/image39.png){width="6.5in"
    height="2.8680555555555554in"}

8.  In the search box (top right corner), **Project Operations
    integration project expenses export entity** to narrow down the
    results. Then select **Project Operations integration project
    expenses export entity (msdyn_expenses)** and wait until the status
    changes to **Running**.

![](./media/image40.png){width="6.5in"
height="1.6805555555555556in"}**IMPORTANT:**Make sure to wait until the
status displays **Running** before proceeding to the next table map.

### Task 12: Configure/Run Project Operations integration entity for hour estimates (msdyn_resourceassignments)

1.  In the search box (top right corner), **Project Operations
    integration entity for hour estimates** to narrow down the results,
    then click on **Project Operations integration entity for hour
    estimates (msdyb_resourceassignments)**.

![](./media/image41.png){width="6.5in" height="1.8395833333333333in"}

2.  On the **Table mappings** tab, in the top ribbon, click **Refresh**
    **tables**.

    ![](./media/image42.png){width="6.490277777777778in"
    height="3.9590277777777776in"}

3.  After the refresh is complete, click on **Run**

    ![](./media/image43.png){width="6.497222222222222in"
    height="4.297916666666667in"}

4.  On the **Initial writes and related table maps(s)** page, click
    **Run**.

    ![](./media/image44.png){width="6.489583333333333in"
    height="1.7770833333333333in"}

5.  On the **Confirmation** dialog box, click **Yes**.

    ![](./media/image27.png){width="4.916666666666667in"
    height="1.9493055555555556in"}

6.  ![](./media/image45.png){width="6.490277777777778in"
    height="3.425in"}Click on **Dual-Write**

7.  In the Search box (top right corner), **Project Operations
    integration project expenses export entity** to narrow down the
    results. Then **Project Operations integration entity for hour
    estimates (msdyn_resourceassignments)** and then wait for the status
    to change to **Running**.

![Graphical user interface Description automatically generated with
medium confidence](./media/image46.png){width="6.256944444444445in"
height="1.5208333333333333in"}

**IMPORTANT:** Make sure to wait until the status displays **Running**

8.  Close the **Finance and Operations** tab.
