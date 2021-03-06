
   * Click **Sign In**, and then enter the credentials for your Azure account.

     This method is quicker and easier, but if you use this method you won't be able to see Azure SQL 数据库 or Mobile Services in the **Server Explorer** window.

   * Click **Manage subscriptions** in order to install a management certificate that enables access to your account.

     In the **Manage Azure Subscriptions** dialog box, click the **Certificates** tab, and then click **Import**. Follow the directions to download and import a subscription file (also called a *.publishsettings* file) for your Azure account.

     <div class="dev-callout"><strong>Security Note:</strong>
     <p>Download the subscription file to a folder outside your source code directories (for example, in the Downloads folder), and then delete it once the import has completed. A malicious user who gains access to the subscription file can edit, create, and delete your Azure services.</p></div>

   For more information, see [How to Connect to Azure from Visual Studio](http://go.microsoft.com/fwlink/?LinkId=324796).
