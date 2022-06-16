</head><body><h1 id='temp:C:UVE9c60e60a019f4415b34781ab6'>A-HLS Provider Claim Payment Dispute Workflow Documentation</h1>

<i>A guided decision flow for providers to quickly view their claim payment details from a health plan and raise a dispute for a payment.</i><br/>

<h2 id='temp:C:UVEb22236ddb07c4a40b6daf9d08'>Overview</h2>

<span style="color:#333333" textcolor="#333333">Provider Claim Payment Dispute Workflow is a guided workflow for providers to quickly view their claim payment details from a health plan and raise a dispute for a claim payment transaction if needed. </span><br/>

<span style="color:#333333" textcolor="#333333">This process typically happens after a provider files a claim on behalf of a patient. The flow can be called from a Digital Process Automation (DPA) Action from a Salesforce Lightning Page or an Experience Cloud Community. </span><br/>

<h4 id='temp:C:UVE0c0dda68c00a4f6e9eee5a6ca'><span style="color:#333333" textcolor="#333333">Use Case Scenario</span></h4>

<span style="color:#333333" textcolor="#333333">As a provider, I need to see all my claims with payment details and be able to go through a guided process to log a dispute with the associated health plan for a claim if needed.</span><br/>

<br/>

<div data-section-style='11' style='max-width:100%' class=''><img src='https://quip.com/blob/UVEAAAlVpDp/gzBqDBCpVyjmhByFgoVmUg?a=lGkzd7hyqsM4U1MVfAIg8hHKyqnAbilq5JebY2tK6cQa' id='temp:C:UVE857a81adef8f4937981371d93' width='773' height='395' alt="Image showing the workflow a provider would go through when using this accelerator."></img>

<hr style='width:100%'><h2 id='temp:C:UVE87f6d1a776bc42f3b508505ff'>Business Objective</h2>

<span style="color:#333333" textcolor="#333333">The business objective is to provide a fast and intuitive way for providers to register their disputes with the health plans for the claim payments they receive. </span><br/>

<h2 id='temp:C:UVE5d35df07311c4d39a8b6232f4'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVE4f12e25c9de9484e83b760141'><li id='temp:C:UVE56ee0a0d83764208af6ebcfcd' class='' value='1'><span style="color:#333333" textcolor="#333333">Reduction in administrative costs of handling provider claim payment disputes.</span>

<br/></li><li id='temp:C:UVEd1b6e89936b44dcfaaeb013d6' class=''><span style="color:#333333" textcolor="#333333">Improvement in provider NPS/satisfaction with the health plan.</span>

<br/></li><li id='temp:C:UVE49ae270ca74b435a99b313f6a' class=''><span style="color:#333333" textcolor="#333333">Improvement in provider retention/renewal rate.</span>

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:UVE666231e8d4fe4f1eb31a44721'>User Story</h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVE1c2a5e8ffe8444fdad0c00544'><li id='temp:C:UVE71bd4045266b4334b0607c476' class='' value='1'>Step 1: Provider logs in to the Digital Community.

<br/></li><li id='temp:C:UVEb895dec999bf462ebd7ede848' class=''>Step 2: Provider navigates to the Claim Payment Card. It shows the list of claims associated with the provider with payment details. 

<br/></li><li id='temp:C:UVE705d9333488d4843ab2e31a02' class=''>Step 3: The provider verifies the claims payments from the health plan.

<br/></li><li id='temp:C:UVEa7c206f96f45432fa8809ce82' class=''>Step 4: The provider logs a dispute by clicking the Dispute link.

<br/></li><li id='temp:C:UVE26db6b6902d84432802a1a376' class=''>Step 5: The provider enters the required details for disputing a payment.

<br/></li><li id='temp:C:UVEb5ea98c60d0a474da261913dd' class=''>Step 6: A case is created with the details entered. 

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:UVEb7ec83a6db4145ea8da6a64d7'>Package Includes</h2>

<h3 id='temp:C:UVE3173986d45ac440abbf37fe90'><br><b><span style="color:#333333" textcolor="#333333">OmniScript (1)</span></b></h3>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVEb686943749214b77bd1eb2a8b'><li id='temp:C:UVE7245a2c0297f4d9184c1ca13d' class='' value='1'><span style="color:#181818" textcolor="#181818">A-HLS-OSDisputeProviderClaimPayment</span>

<br/></li></ul></div><h3 id='temp:C:UVEc2080fa598e447eeadedb862a'><b>DataRaptor (6)</b></h3>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVEa512be202de94cb29e2e412f1'><li id='temp:C:UVE230a71ad705349829126f5e31' class='' value='1'>DRGetPractitionerClaims

<br/></li><li id='temp:C:UVE4eb0c1726d3748e29d23941ad' class=''>DRGetProviderClaims

<br/></li><li id='temp:C:UVEb51e37c526c24b5994aa0dd51' class=''>DRClaimPaymentExtract

<br/></li><li id='temp:C:UVEb01a73b5806844a88a36ee95e' class=''>DRSupportCaseRecordTypeExtract

<br/></li><li id='temp:C:UVEafc72bc595af4f7087510a815' class=''>DRCreateCaseForClaimPayment

<br/></li><li id='temp:C:UVE65895ba511af4574b6ff95fd9' class=''>DRCaseIDExtract

<br/></li></ul></div><h3 id='temp:C:UVE99049d12d4a04a81a8045fbd1'><b>OmniStudio FlexCards (1)</b></h3>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVE7d363d6a2c6b4552b249f6199'><li id='temp:C:UVE441910dd8b29463094b3bd639' class='' value='1'>FCProviderClaimPaymentDispute

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:UVEbe97e85e216041eb898e8d49f'>Configuration Requirements</h2>

<h3 id='temp:C:UVE0a722c4951b845f68ed7b02d3'>Installation Instructions:</h3>

The following steps are required for installation.<br/>

<h4 id='temp:C:UVE7e5d788d58bb44979ac345859'>Install the Data Pack</h4>

<div data-section-style='6' class="" style=""><ul id='temp:C:UVE8595f1b43ff046ebbe3999fc2'><li id='temp:C:UVEb630881d23b545878201e02ad' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/Provider-Claim-Dispute-Workflow">https://github.com/HLS-Accelerate/Provider-Claim-Dispute-Workflow</a>.

<br/></li><li id='temp:C:UVE9fbb046ee4bc4fcc96fc4b6a5' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='temp:C:UVE16b28596035046cc947fecc27' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='temp:C:UVE97c19fe42e9740048896aa78e' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='temp:C:UVE8ee629bd80e64764a853c6eb9' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul></ul></div><h3 id='temp:C:UVE2e6ae37f74eb419eba715e746'>Post-Install Configuration Requirements:</h3>

<div data-section-style='6' class="" style=""><ul id='temp:C:UVE42a8c9f9e044411c8293810ba'><li id='temp:C:UVEb71e456a3b4d4e8f87e567e9a' class='parent' value='1'>To provide your users access to the Cases/Claims List Views:

<br/></li><ul><li id='temp:C:UVEf446da1120ee4e8080c32c655' class=''>Create a Permission Set that grants appropriate access to the desired object. 

<br/></li><li id='temp:C:UVE0b47b34bb793407890ceab893' class=''>Add the Permission set to the end user Profile to grant access to the desired object. 

<br/></li><li id='temp:C:UVE8efa60e9a27c4e50a17945af1' class=''>Repeat steps A and B above for each desired object. 

<br/></li></ul><li id='temp:C:UVEb4a7dd278d114f8b977bc362d' class=''>Activate the FlexCard that you imported with the Data Pack above. Please refer to the following help article for more information on how to activate a FlexCard: <a href="https://docs.vlocity.com/en/Activate-a-FlexCard.html">https://docs.vlocity.com/en/Activate-a-FlexCard.html</a>.

<br/></li><li id='temp:C:UVEbaa060ed17db4265bf549610c' class=''>Add the FlexCard LWC to the desired Lightning Page. For more information on how to add Lightning Web Components to a page, please refer to this help article: <a href="https://docs.vlocity.com/en/Add-a-FlexCard-to-a-Lightning-Page.html">https://docs.vlocity.com/en/Add-a-FlexCard-to-a-Lightning-Page.html</a>.

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:UVE255736a50d1d4ab8a2e1174f6'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVE67e8f926f3894ff4a12d00907'><li id='temp:C:UVE385a1d0397214d9bac504be69' class='' value='1'>A customer has licenses for Experience Cloud, Health Cloud, and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='temp:C:UVEf8884b5e765c408f8000cb9e2' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='temp:C:UVE13e22ea50d4147ac829521832' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.

<br/></li><li id='temp:C:UVEbf6f7b3b854248958391066b1' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved. 

<br/></li><li id='temp:C:UVE70a465bd55c042b988f3a1cd2' class=''><span style="color:#333333" textcolor="#333333">Claims and Claim Payments are available in Salesforce.</span>

<br/></li><li id='temp:C:UVE48efef9ea9144499a00cfa116' class=''>The process works in the context of a claim payment Id of a claim. 

<br/></li><li id='temp:C:UVE663c00cb56e047baa8b0aac50' class=''>The card runs in the context of the logged-in users’ Id.

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:UVE805f6272e05b4073b0f3cc563'>Revision History</h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:UVE41389a3f86c5462aabd20c812'><li id='temp:C:UVE2244ac776e7e4f4a81ad23d2b' class='parent' value='1'><b>Revision Short Description (Sep 04, 2019)</b>

<br/></li><ul><li id='temp:C:UVE87e9be4c16a7492fbe98b11aa' class=''>Used a custom object for getting claim payment details. 

<br/></li><li id='temp:C:UVEfc807034637d48f18258fc435' class=''>Used three custom fields in<span style="color:#8e8e8e" textcolor="#8e8e8e"> </span><b>Claim</b><span style="color:#8e8e8e" textcolor="#8e8e8e"> </span>and<span style="color:#8e8e8e" textcolor="#8e8e8e"> </span><b>Case</b><span style="color:#8e8e8e" textcolor="#8e8e8e"> </span>object. Details are in the <b>Custom Fields<span style="color:#8e8e8e" textcolor="#8e8e8e"> </span></b>zip file. 

<br/></li></ul><li id='temp:C:UVE9570ea632c6c4c519f865e090' class='parent'><b>Revision Short Description (Oct 09, 2019)</b>

<br/></li><ul><li id='temp:C:UVE664935c668174095a228c1fe8' class=''>Removed all customizations and used package objects.

<br/></li></ul><li id='temp:C:UVE706b357ef1d54c2182c9ef508' class='parent'><b>Revision Short Description (Jun 13, 2022)</b>

<br/></li><ul><li id='temp:C:UVE920a2d1bc2a744978c5ebbda2' class=''>Converted the OmniScript to LWC.

<br/></li><li id='temp:C:UVE552012b1acbc4382b936dd5b2' class=''>Fixed the associated DataRaptors (see list in the "Package Includes", "DataRaptor" Section).

<br/></li><li id='temp:C:UVE05f606699c914b748e52fd1de' class=''>Vlocity Card 'VPL-ProviderClaims-105' converted into a FlexCard ("FCProviderClaimPaymentDispute").

<br/></li><li id='temp:C:UVE036fbc2d70ee449da35d7be6e' class=''>Added installation steps and assumptions.

<br/></li></ul></ul></div></body></html>
