# Create a Logic App

## Overview
Azure Logic Apps is a cloud platform where you can create and run automated workflows in, across, and outside the software ecosystems in your enterprise or organization. 

## Tasks to be completed
1.Create a logic app.

2.Creating the work flow.

3.Send a mail through outlook.

## Task:1 Create a logic app

### Step 1: Sign in to Azure Portal

1. Open your browser and go to [https://portal.azure.com](https://portal.azure.com).
2. Log in using your Azure credentials.

### Step 2: Create a New Logic App 
1. **Navigate to the Search bar (1)** and **search Logic apps (2)**.
   
   ![](https://github.com/Tejees/logic-app/blob/main/1.png)

2. Once Logic app is opened navigate to **+Add (2)** on the top left.

   ![](https://github.com/Tejees/logic-app/blob/main/2.png)

3. Once we click add option it shows hosting plans in that we have to **workflow Service Plan in standard (1)** and **select (2)**.

   ![](https://github.com/Tejees/logic-app/blob/main/3.png)

4. Fill the details under **Basics tab (1)**
  -In project details fill the **Subscription (2)** and **Resource group (3)**.

  -Under Instance details fill **logic name (4)**, **region (5)** and **windows plan (6)**.

   ![](https://github.com/Tejees/logic-app/blob/main/4.png)

5. Click Storage tab Under **storage tab (1)** the steps to be followed
   -Select the existing **storage account (2)**, select **Storage type by default Azure Storage (3)** is Present and click **Review+Create (4)**.

    ![](https://github.com/Tejees/logic-app/blob/main/5.1.png)

6. After clicking Review+Create

   -It validates all the steps in **Review+Create (1)** then it allows you to **create (2)** the logic app.

    ![](https://github.com/Tejees/logic-app/blob/main/6.png)

7. Then Logic app is going to be deployed.
   
   -After deployement **go to resource (1)** tab.

    ![](https://github.com/Tejees/logic-app/blob/main/7.png)

## Task 2: Creating a workflow

### Step 1: After Creating a Logic app we are going to create workflow.

1. In the Overview of Logic app Click the **workflow (1)** and select **workflows (2)** in the left side bar.

   ![](https://github.com/Tejees/logic-app/blob/main/8.png)

2. Click **+Add (1)** on top left and select **Add from template (2)**.

   ![](https://github.com/Tejees/logic-app/blob/main/9.png)

### Step:2 Templates are shown in the page

1. In that Template select **Blank workflow (1)**.

   ![](https://github.com/Tejees/logic-app/blob/main/10.png)

2. Then it shows you to **add a trigger (1)**.
   
   ![](https://github.com/Tejees/logic-app/blob/main/11.png)

3. In the Add a trigger fill the blanks.
   
   -Navigate **search bar and search request (1)**

   -It shows **Request (2)** option in that you have to **Trigger (3)**

    ![](https://github.com/Tejees/logic-app/blob/main/12.png)

### Step 3: When Http request is recived follow the given steps

1. After Http request is recived it shows some parameters.

   ![](https://github.com/Tejees/logic-app/blob/main/13.png)

2. In the **Method (1)** select **Get (2)**.
   
   ![](https://github.com/Tejees/logic-app/blob/main/14.png)

4. Then close that parameters, In Request is Recived navigate to **+ and click on it, add an action**.

   ![](https://github.com/Tejees/logic-app/blob/main/15.png)

5. In the Add a trigger fill the blanks.
   
   -Navigate **search bar and search response (1)**

   -It shows **Response (2)** option in that you have to **Trigger (3)**.

    ![](https://github.com/Tejees/logic-app/blob/main/16.png)

6. In the reponse fill the parameters, In **Body give text Hello World (1)**

   ![](https://github.com/Tejees/logic-app/blob/main/17.png)

7. Navigate to **save** and Click on it.

   ![](https://github.com/Tejees/logic-app/blob/main/18.png)

8. Navigate on **Run (1)** and click it, in the dropdown click **Run (2)**.

    ![](https://github.com/Tejees/logic-app/blob/main/18.1.png)

9. In the Left sided bar under tools click on **code** that shows you request and response code.

    ![](https://github.com/Tejees/logic-app/blob/main/19.png)

10. In the same bar **click Run History**.

    ![](https://github.com/Tejees/logic-app/blob/main/20.png)

11. Again click **when http request is recived (1)** and copy the **url (2)** in the parameters.

    ![](https://github.com/Tejees/logic-app/blob/main/21.png)

12. Copy the URL and Paste in new tab you will get a page as shown in below.

    ![](https://github.com/Tejees/logic-app/blob/main/22.png)

## Task 3: Send an Email through outlook

### Step 1: For the same request add the another action.

1. Click **+ Add an action it**.

   ![](https://github.com/Tejees/logic-app/blob/main/23.png)

2. In Add on actions **search outlook in search bar (1)** and select **send an email (2)**.

   ![](https://github.com/Tejees/logic-app/blob/main/24.png)

3. In the Parameters fill the details.

   -Mention **TO (1)** whom you are sending a mail.
   -Add the **subject (2)**.
   -In the **Body (3)** fill the Content.

   ![](https://github.com/Tejees/logic-app/blob/main/25.png)

4.Click **Save** on top.

  ![](https://github.com/Tejees/logic-app/blob/main/26.png)

5. Navigate on **Run** and click it.

   ![](https://github.com/Tejees/logic-app/blob/main/27.png)

6. Open in gmail in your browser.

   ![](https://github.com/Tejees/logic-app/blob/main/29.png)


    



    
   
