# Azure_Cloud_Projects
#Here is a simple repository where I drop all Azure projects.

Here’s a step-by-step guide for implementing each of these 10 beginner-friendly projects in the Azure portal:

---

### 1. **Simple Website Hosting with Azure App Service**

1. **Navigate to Azure App Service**:
   - In the Azure portal, search for **App Service** and select **Create**.

2. **Configure App Service**:
   - Choose your **Subscription** and **Resource Group**.
   - Give the app a unique **Name**, select **Runtime stack** (e.g., .NET, Node.js, Python), and set the **Region**.

3. **Deploy Website Code**:
   - Under **Deployment**, choose **Deploy from source** (GitHub, Azure Repos, etc.), or manually upload the website files.

4. **Test and Access Website**:
   - Once deployed, click on the **URL** provided to access the website.

---

### 2. **Create a Virtual Network and Secure It with Network Security Groups (NSGs)**

1. **Create a Virtual Network (VNet)**:
   - Search for **Virtual Network** in the Azure portal and select **Create**.
   - Choose your **Subscription**, **Resource Group**, and provide a **Name**.
   - Configure **Address Space** and **Subnet**.

2. **Create a Network Security Group (NSG)**:
   - Search for **Network Security Group**, select **Create**.
   - Configure **Inbound** and **Outbound rules** for your specific traffic needs.

3. **Attach NSG to VNet**:
   - Go to **Subnets** under the VNet settings and associate your NSG with the subnet.

---

### 3. **Deploy a Virtual Machine and Install Software Using Azure VM Extensions**

1. **Create a Virtual Machine**:
   - Search for **Virtual Machine** and select **Create**.
   - Configure **Region**, **Image** (choose OS), and **Size**.
   - Set **Username** and **Password** for access.

2. **Add Inbound Security Rules**:
   - Go to **Networking** tab, add rules to allow SSH (Linux) or RDP (Windows).

3. **Deploy Software Using Extensions**:
   - After VM creation, navigate to the **Extensions** section.
   - Select an extension (e.g., Custom Script Extension), and upload a script to install software like Apache or Nginx.

4. **Connect to VM**:
   - Use SSH or RDP to verify that the software has been installed.

---

### 4. **Set Up Azure Blob Storage for File Storage and Management**

1. **Create a Storage Account**:
   - Search for **Storage Account**, select **Create**.
   - Provide **Resource Group**, **Storage Account Name**, and **Region**.

2. **Create a Blob Container**:
   - In the Storage Account, go to **Containers** and select **+ Container**.
   - Name your container and set access level (public/private).

3. **Upload Files**:
   - Click on the container and upload files directly through the portal.

---

### 5. **Build a Serverless Function with Azure Functions**

1. **Create an Azure Function App**:
   - Search for **Function App** and select **Create**.
   - Choose **Runtime Stack** (e.g., JavaScript, C#), **Region**, and **Hosting Plan**.

2. **Set Up the Function**:
   - After creation, go to the Function App and add a new function with an **HTTP Trigger** or other triggers.

3. **Write and Deploy Function Code**:
   - Use the **Code + Test** section to write the function code.

4. **Test the Function**:
   - Go to **Get Function URL** and use the provided URL to test your function.

---

### 6. **Automate Resource Deployment Using ARM Templates**

1. **Use the Azure Quickstart Template**:
   - In the Azure portal, go to **Templates** and select **+ Create a Template**.

2. **Choose or Write an ARM Template**:
   - Use a pre-existing template or create a JSON template from scratch.

3. **Deploy ARM Template**:
   - Select **Deploy** and fill out any required parameters to automatically deploy resources like VMs or storage.

---

### 7. **Build a Simple Azure SQL Database and Connect to It**

1. **Create SQL Database**:
   - Search for **SQL Database** and select **Create**.
   - Provide **Database Name**, **Server Name** (create a new one), and **Authentication** method.

2. **Configure Firewall**:
   - After creation, go to **Networking** and add your local IP under **Firewall Rules**.

3. **Connect to Database**:
   - Use tools like Azure Data Studio or SQL Server Management Studio (SSMS) with the **Server Name**, **Username**, and **Password**.

4. **Create Tables and Insert Data**:
   - Run SQL queries to create tables and insert test data.

---

### 8. **Create an API with Azure API Management**

1. **Create API Management Instance**:
   - Search for **API Management Services** and select **Create**.
   - Configure **Instance Name**, **Region**, and **Pricing Tier**.

2. **Create and Configure API**:
   - After creation, go to **APIs** > **+ Add API**.
   - Use a template or import from a Swagger file if you have an existing API.

3. **Set Security and Access**:
   - Configure **API Keys** or **OAuth** as needed to secure access.

4. **Test API**:
   - Use the **Developer Portal** to test the API and verify it’s working as expected.

---

### 9. **Set Up Azure Monitor to Track Resource Performance**

1. **Enable Azure Monitor**:
   - In the Azure portal, search for **Monitor** and open the **Insights** for your resource (e.g., VM).

2. **Configure Alerts**:
   - In **Alerts**, create **New alert rule**.
   - Set **Condition** (e.g., CPU usage > 80%), **Action group**, and **Alert Details**.

3. **Analyze Logs**:
   - Use **Log Analytics** under Monitor to view detailed metrics and logs.

---

### 10. **Implement Load Balancing with Azure Load Balancer**

1. **Create a Load Balancer**:
   - Search for **Load Balancer** in the portal and select **Create**.
   - Configure **Load Balancer Type** (Public/Private), **Region**, and **Resource Group**.

2. **Add Backend Pool**:
   - After creation, go to **Backend Pools** and add your VMs as backend servers.

3. **Create Health Probes and Load Balancing Rules**:
   - Set up **Health Probes** for monitoring and **Load Balancing Rules** for traffic distribution.

4. **Test Load Balancer**:
   - Access the public IP of the load balancer to ensure traffic is being distributed.

---

These steps will give you foundational experience across key Azure services and incrementally build your cloud engineering skills. Feel free to let me know if you need any more details on specific steps or services!

Here is my YouTube channel for more audio-visual content: https://www.youtube.com/@TheCloudJourney-HQ
