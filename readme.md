<h2>DESCRIPTION</h2>
<p>The project utilizes Azure QNA Maker serrvice to create a knowledge base and a backend for our portal, where all the asked questions are queued against. The QNA Maker is then deployed and a Azure Bot is inherits. The bot service is embedded into the frontend through web chat channel offering. And the frontend i.e a static website is hosted using azure storage account
    <h3>Hosted at: https://covid19qnastorage.z13.web.core.windows.net/</h3>
</p>

<h2>SERVICES USED:</h2>
<ul>
    <li>QNA Maker</li>
    <li>Azure Bot Service</li>
    <li>Azure Storage</li>
</ul>

<h3>Data resource: https://www.who.int/emergencies/diseases/novel-coronavirus-2019/question-and-answers-hub</h3>
<h2>Service costing:</h2>
<ul>
    <li>QNA Maker - Free F0</li>
    <li>Azure Search pricing tier - Free F(3 indexes)</li>
    <li>Azure Bot service - F0 Free</li>
    <li>Azure Storage Account - StorageV2 (general purpose v2)</li>
</ul>

